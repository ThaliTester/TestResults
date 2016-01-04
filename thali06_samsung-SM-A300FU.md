#### Test 54970261c23922d_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  290): DCD OFF
--------- beginning of system
D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/AndroidRuntime( 5388): 
D/AndroidRuntime( 5388): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5388): CheckJNI is OFF
D/AndroidRuntime( 5388): readGMSProperty: start
D/AndroidRuntime( 5388): readGMSProperty: already setted!!
D/AndroidRuntime( 5388): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5388): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5388): readGMSProperty: end
D/AndroidRuntime( 5388): addProductProperty: start
E/AffinityControl( 5388): AffinityControl: registerfunction enter
D/AndroidRuntime( 5388): Calling main entry com.android.commands.am.Am
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
E/Zygote  ( 5400): MountEmulatedStorage()
E/Zygote  ( 5400): v2
I/libpersona( 5400): KNOX_SDCARD checking this for 10338
I/libpersona( 5400): KNOX_SDCARD not a persona
I/SELinux ( 5400): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5400): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5400): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=11 createSurf (1x1),1 flag=404, uhalitest
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5400 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1020): Focused application set to: xxxx
D/InputDispatcher( 1020): Focus left window: 1478
D/TimaKeyStoreProvider( 5400): TimaSignature is unavailable
D/AndroidRuntime( 5388): Shutting down VM
D/ActivityThread( 5400): Added TimaKeyStore provider
V/WindowManager( 1020): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1020): isKioskContainerExistOnDevice
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1478): updateVisibility : ActivityRecord{e928034 token=android.os.BinderProxy@1f75225f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1478): onTrimMemory. Level: 20
I/WebViewFactory( 5400): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5400): Time to load native libraries: 1 ms (timestamps 2180-2181)
I/LibraryLoader( 5400): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5400): Binding Chromium to main looper Looper (main, tid 1) {bf7811a}
I/LibraryLoader( 5400): Expected native library version number "",actual native library version number ""
I/chromium( 5400): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 5388): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/BrowserStartupController( 5400): Initializing chromium process, singleProcess=true
,W/art     ( 5400): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5400): ApplicationContext is null in ApplicationStatus
,W/chromium( 5400): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5400): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5400): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5400): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5400): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5400): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5400): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5400): Local Branch: 
I/Adreno-EGL( 5400): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5400): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5400):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/BluetoothAdapter( 5400): 588481748: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5400): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5400): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5400): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5400): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5400): CordovaWebView is running on device made by: samsung
,W/art     ( 5400): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5400): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1020): Activity pause timeout for ActivityRecord{3e0d4c6c u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 5400): Render dirty regions requested: true
,D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
,D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,W/chromium( 5400): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 5400): updateVisibility : ActivityRecord{128bcb04 token=android.os.BinderProxy@378a0396 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 5400): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 5400): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1020): Focus entered window: 5400,
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 5400): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5400): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5400): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 5400): Enabling debug mode 0
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 5400): showStatusIcon on inactive InputConnection
,I/Timeline( 5400): Timeline: Activity_idle id: android.os.BinderProxy@378a0396 time:152751
,I/ActivityManager( 1020): Displayed Component not be shown by security: +748ms (total +46s184ms)
,W/ActivityManager( 1020): mDVFSHelper.release()
,I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{3e0d4c6c u0 com.test.thalitest/.MainActivity t20} time:152788
,I/SurfaceFlinger(  259): id=11 Removed uhalitest (7/9)
,I/SurfaceFlinger(  259): id=11 Removed uhalitest (-2/9)
,I/SamsungIME( 1781): getCurrentCandidateView
,W/BindingManager( 5400): Cannot call determinedVisibility() - never saw a connection for the pid: 5400
,D/SamsungIME( 1781): Dismiss ExpandCandiate
,I/SamsungIME( 1781): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1781): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1781): KeybaordView init() : load resources
,I/SamsungIME( 1781): getCurrentKeyboard
,I/SamsungIME( 1781): getTextKeyboard
,D/SamsungIME( 1781): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 5400): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5400): JniHelper::setJavaVM(0xb759a448), pthread_self() = -1213271008
,D/JX-Cordova( 5400): jxcore cordova android initializing
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,W/jxcore-log( 5400): Initializing JXcore engine
W/jxcore-log( 5400): JXcore engine is ready
,W/jxcore-log( 5400): Starting JXcore engine
,E/audit   ( 1777): type=1400 msg=audit(1451923489.601:203): avc:  denied  { ioctl } for  pid=5400 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1777):  SEPF_SM-A300FU_5.0.2_0027
,E/audit   ( 1777): type=1300 msg=audit(1451923489.601:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=bede2d58 items=0 ppid=307 ppcomm=main pid=5400 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1777): type=1320 msg=audit(1451923489.601:203): 
,W/jxcore-log( 5400): Platform android
W/jxcore-log( 5400): 
W/jxcore-log( 5400): Process ARCH arm
W/jxcore-log( 5400): 
,I/jxcore-log( 5400): JXcore Cordova bridge is ready!
I/jxcore-log( 5400): 
,W/jxcore-log( 5400): JXcore engine is started
,I/chromium( 5400): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5400): Toggling radios to true
I/jxcore-log( 5400): 
,D/BluetoothAdapter( 5400): enable()
,W/ActivityManager( 1020): Permission Denial: getCurrentUser() from pid=5400, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 1020): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 1020): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5400, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 1020): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/BluetoothManagerService( 1020): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
W/BluetoothManagerService( 1020): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
W/BluetoothManagerService( 1020): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/BluetoothManagerService( 1020): 	at android.os.Binder.execTransact(Binder.java:461)
,E/DevicePolicyManagerService( 1020): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1020): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider( 1020): name = bluetooth_on
,E/DevicePolicyManagerService( 1020): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1020): getAllowBluetoothMode - value retunrs : 2
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5451): MountEmulatedStorage()
,E/Zygote  ( 5451): v2
I/libpersona( 5451): KNOX_SDCARD checking this for 1002
I/libpersona( 5451): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5451 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
I/SELinux ( 5451): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/SecContentProvider( 1020): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1020): uri = 20 selection = isWifiStateChangeAllowed,
D/SecContentProvider2( 1020): mCursor = null
,I/SELinux ( 5451): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 5451): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiService( 1020): setWifiEnabled: true pid=5400, uid=10338
W/ActivityManager( 1020): Permission Denial: getCurrentUser() from pid=5400, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1020): Failed getting userId using ActivityManagerNative
W/WifiService( 1020): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5400, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1020): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1020): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1020): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1020): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1020): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1020): name = wifi_on
,I/WifiService( 1020): disconnect: pid=5400, uid=10338
,E/WifiHW  ( 1020): ##################### set firmware type 0 #####################
,I/jxcore-log( 5400): Radios toggled
I/jxcore-log( 5400): 
D/TimaKeyStoreProvider( 5451): TimaSignature is unavailable
D/ActivityThread( 5451): Added TimaKeyStore provider
,W/ResourcesManager( 5451): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 5451): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni( 5451): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 5451): Adding GattService
,D/BtSettings.ProfileConfig( 5451): Adding HeadsetService
,D/BtSettings.ProfileConfig( 5451): Adding A2dpService
,D/BtSettings.ProfileConfig( 5451): Adding HidService
,D/BtSettings.ProfileConfig( 5451): Adding HealthService
,D/BtSettings.ProfileConfig( 5451): Adding PanService
D/BtSettings.ProfileConfig( 5451): Adding BluetoothMapService
,D/BtSettings.ProfileConfig( 5451): Adding SapService
D/BtSettings.ProfileConfig( 5451): Adding HeadsetClientService
,D/BtSettings.ProfileConfig( 5451): Adding A2dpSinkService
,D/BtSettings.ProfileConfig( 5451): Adding SapClientService
D/BtSettings.ProfileConfig( 5451): Adding HidDevService
,I/BtSettings.ProfileConfig( 5451): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 1020): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 1002
,D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/SettingsProvider( 1020): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 1002
,D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1020): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
,D/SettingsProvider( 1020): selectionArgs: 1002
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1020): ret = -1
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1020): name = bt_svcst_com.android.bluetooth.hid.HidService
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
,D/SettingsProvider( 1020): selectionArgs: 1002
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1020): ret = -1
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
D/SettingsProvider( 1020): name = bt_svcst_com.android.bluetooth.hdp.HealthService
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1020): selectionArgs: false
,D/SettingsProvider( 1020): selectionArgs: 1002
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1020): ret = -1
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/SettingsProvider( 1020): name = bt_svcst_com.android.bluetooth.pan.PanService
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 1002
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1020): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 1002
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1020): name = bt_svcst_com.broadcom.bt.service.sap.SapService
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1020): selectionArgs: false
I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/SettingsProvider( 1020): selectionArgs: 1002
,D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1020): ret = -1
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/SettingsProvider( 1020): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
,D/SettingsProvider( 1020): selectionArgs: 1002
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1020): ret = -1
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/SettingsProvider( 1020): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 1002
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1020): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 1002
,D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/SettingsProvider( 1020): name = bt_svcst_com.android.bluetooth.hid.HidDevService
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 1002
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1020): ret = -1
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/BluetoothAdapterState( 5451): make
,I/bluedroid( 5451): init
,I/BluetoothAdapterState( 5451): Entering OffState
,I/bte_conf( 5451): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5451): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 5451): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5451): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 5451): btif_fetch_local_ble_random_bdaddr
,I/bluedroid( 5451): get_profile_interface socket
I/bluedroid( 5451): get_profile_interface map_client
,D/BluetoothAdapterService( 5451): checkAddrForIOP: Loading from conf
,I/GKI_LINUX( 5451): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 5451): Address is:08:EC:A9:50:75:41
,E/BluetoothServiceJni( 5451): populateRssiValuesNative
I/bluedroid( 5451): getModelRssiValues
E/BluetoothServiceJni( 5451): model_rssi_values_callback: low = -70, mid = -60, high = 127
,D/BluetoothAdapterProperties( 5451): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/SettingsProvider( 1020): name = bluetooth_name
,D/BluetoothAdapterProperties( 5451): Name is: A3-1
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/bluedroid( 5451): config_hci_snoop_log
,D/BluetoothManagerService( 1020): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothManagerService( 1020): Ble is always on enable gatt
,I/BluetoothManagerService( 1020): enableGattForLeMode, doBind called
,E/DevicePolicyManagerService( 1020): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1020): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider( 1020): uri = 3 selection = isBluetoothEnabled
,I/BtGatt.JNI( 5451): classInitNative(L900): classInitNative: Success!
,D/BluetoothManagerService( 1020): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/BluetoothAdapterState( 5451): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties( 5451): Setting state to 11
I/BluetoothAdapterState( 5451): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 5451): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5451): updateAdapterState state is 11
D/BluetoothAdapterService( 5451): Autoconnection is available 
D/BluetoothAdapterService( 5451): updateAdapterState prevState = 10newState = 11
,D/BluetoothSecureManager( 5451): getInstant: null
,D/BluetoothSecureManager( 5451): calling getMethod for getService
D/BluetoothSecureManager( 5451): calling getService
D/BluetoothSecureManager( 5451): getService return binder: android.os.BinderProxy@c00dd79
,D/BluetoothSecureManagerService( 1020): isSecureModeEnabled
,D/BluetoothSecureManagerService( 1020): getSecureModeSetting, name: secure_mode_enable
D/BtConfig.SecureMode( 5451): isSecureModeOn:false
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 5451): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5451): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/InputMethodManagerService( 1020): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
W/BluetoothAdapterService( 5451): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
I/InputMethodManagerService( 1020): [BT Setting State] State =11
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5451): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5451): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5451): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5451): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5451): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5451): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 5451): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 5451): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,D/BluetoothTile( 1181):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1181): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1181):  getBluetoothState : 11
,W/BluetoothAdapterService( 5451): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/BluetoothBondStateMachine( 5451): make
,D/BluetoothTile( 1181):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1181): onStateChanged: Bluetooth
,I/SamsungIME( 1781): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/StatusBarManagerService( 1020): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1020): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1181): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,W/BluetoothAdapterService( 5451): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5451): Not skipping com.android.bluetooth.gatt.GattService
,I/BluetoothBondStateMachine( 5451): StableState(): Entering Off State
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5451): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5451): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.DebugUtils( 5451): handleDebugAction() action=null
,D/BtGatt.GattService( 5451): Received start request. Starting profile...
D/BtGatt.GattService( 5451): start()
D/BtGatt.GattService( 5451): start()
I/bluedroid( 5451): get_profile_interface gatt
D/BluetoothAdapterService( 5451): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67dae28
,D/BtGatt.AdvertiseManager( 5451): advertise manager created
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5451): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 5451): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5451): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 5451): Not skipping com.android.bluetooth.hid.HidService
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BtGatt.GattService( 5451): mStartError = false
D/BluetoothAdapterService( 5451): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67dae28
,W/BluetoothAdapterService( 5451): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5451): Not skipping com.android.bluetooth.hdp.HealthService
,D/HeadsetService( 5451): Received start request. Starting profile...
,D/HeadsetService( 5451): start()
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothHeadsetServiceJni( 5451): classInitNative: succeeds
,W/BluetoothAdapterService( 5451): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5451): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothNotiBroadcastReceiver( 1296): onReceive
D/HeadsetStateMachine( 5451): make
,E/HeadsetStateMachine( 5451): # of Max HF connection is 2
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,V/BluetoothStatusReceiver( 1181): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1181): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,W/BluetoothAdapterService( 5451): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5451): Not skipping com.android.bluetooth.map.BluetoothMapService
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5492): MountEmulatedStorage()
E/Zygote  ( 5492): v2
I/libpersona( 5492): KNOX_SDCARD checking this for 10055
,I/libpersona( 5492): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5492 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 5492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom,
,I/bluedroid( 5451): get_profile_interface handsfree
I/SELinux ( 5492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
E/SELinux ( 5492): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/BluetoothAdapterService( 5451): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5451): Not skipping com.broadcom.bt.service.sap.SapService
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5451): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5451): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5451): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5451): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5451): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5451): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5451): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5451): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 5451): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 5451): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/DualScoManager( 5451): Instantiating Dual Sco Manager
I/DualScoManager( 5451): Set HeadsetServiceHelper
D/BluetoothAtMessage( 5451): createCMTIContentObservers
,D/SettingsProvider( 1020): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed,
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 1002
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine( 5451): Enter Disconnected: -2
,D/HeadsetService( 5451): mStartError = false
D/BluetoothAdapterService( 5451): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67dae28
,D/BluetoothA2dp( 1020): Proxy object connected
,D/HeadsetStateMachine( 5451): Clear mHeadsetBrsf
D/HeadsetStateMachine( 5451): map size, before remove : 0
D/HeadsetStateMachine( 5451): map size, after remove: 0
,D/A2dpService( 5451): Received start request. Starting profile...
D/A2dpService( 5451): start()
,I/BluetoothAvrcpServiceJni( 5451): classInitNative: succeeds
I/bluedroid( 5451): get_profile_interface avrcp
,D/TimaKeyStoreProvider( 5492): TimaSignature is unavailable
,D/ActivityThread( 5492): Added TimaKeyStore provider
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,E/RemoteController( 5451): Cannot set synchronization mode on an unregistered RemoteController
,D/Tethering( 1020): interfaceAdded wlan0
,I/WifiHW  (  280): wifi_change_fw_path(): fwpath = sta
,D/SoftapController(  280): Softap fwReload - Ok
,I/Avrcp   ( 5451):  Updating now playing list upon AVRCP Start
,D/BluetoothMediaBrowser( 5451):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/BluetoothA2dpServiceJni( 5451): classInitNative: succeeds
D/A2dpStateMachine( 5451): make
,I/bluedroid( 5451): get_profile_interface a2dp
,I/GKI_LINUX( 5451): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 5451): warning : media task started media_task_refcnt 1 
,D/A2dpService( 5451): mStartError = false
D/BluetoothAdapterService( 5451): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67dae28
,E/BluetoothAdapterService(108899880)( 5451): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,D/A2dpStateMachine( 5451): Enter Disconnected: -2
,D/BluetoothMediaBrowser( 5451): no now playing list
,D/BluetoothMediaBrowser( 5451):  getNowPlayingId now playing id : -1
,E/Tethering( 1020): No numeric data
,D/Tethering( 1020): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1020): clearTetheredNotification()
,D/NtpTrustedTime( 1020): forceRefresh() from cache miss
,D/UserAnalysis.PlaceProvider( 5492): PlaceProvider onCreate()
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1020): forceRefresh Fail.
,V/NetworkStats( 1020): performPollLocked(flags=0x1),
D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
,V/NetworkStats( 1020): performPollLocked() took 4ms
,D/NtpTrustedTime( 1020): forceRefresh() from cache miss
,D/NtpTrustedTime( 1020): forceRefresh Fail.
,D/HotspotTile( 1181): onReceive : android.net.conn.TETHER_STATE_CHANGED,
,D/HotspotTile( 1181): updateTetherState():false, false
,I/BluetoothHidServiceJni( 5451): classInitNative: succeeds
,I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
,D/HidService( 5451): Received start request. Starting profile...
D/HidService( 5451): start()
I/bluedroid( 5451): get_profile_interface hidhost
D/HidService( 5451): setHidService(): set to: null
D/HidService( 5451): mStartError = false
D/BluetoothAdapterService( 5451): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67dae28
,I/BluetoothHealthServiceJni( 5451): classInitNative: succeeds
,D/HealthService( 5451): Received start request. Starting profile...
D/HealthService( 5451): start()
,D/Tethering( 1020): InitialState.processMessage what=4
,D/Tethering( 1020): interfaceAdded p2p0
,E/Tethering( 1020): No numeric data
,D/Tethering( 1020): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1020): clearTetheredNotification()
,D/Tethering( 1020): p2p0 is not a tetherable iface, ignoring
,I/Nat464Xlat( 1020): interfaceLinkStateChanged p2p0, false
D/Tethering( 1020): interfaceLinkStateChanged p2p0, false
D/Tethering( 1020): interfaceStatusChanged p2p0, false
,D/NtpTrustedTime( 1020): forceRefresh() from cache miss
,D/NtpTrustedTime( 1020): forceRefresh Fail.
,V/NetworkStats( 1020): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
,I/bluedroid( 5451): get_profile_interface health
,D/HotspotTile( 1181): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1181): updateTetherState():false, false
,D/HealthService( 5451): mStartError = false
V/NetworkStats( 1020): performPollLocked() took 2ms
D/BluetoothAdapterService( 5451): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67dae28
,I/BluetoothPanServiceJni( 5451): classInitNative(L105): succeeds
,D/UserAnalysis.SecureDbManager( 5492): Key for secure DB is newly created
,D/NtpTrustedTime( 1020): forceRefresh() from cache miss
,D/NtpTrustedTime( 1020): forceRefresh Fail.
,D/PanService( 5451): Received start request. Starting profile...
D/PanService( 5451): start()
D/BluetoothPanServiceJni( 5451): initializeNative(L110): pan
I/bluedroid( 5451): get_profile_interface pan
,D/PanService( 5451): mStartError = false
D/BluetoothAdapterService( 5451): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67dae28
D/HeadsetStateMachine( 5451): Proxy object connected
,D/BluetoothPan( 1020): BluetoothPAN Proxy object connected
,D/BluetoothMapService( 5451): Received start request. Starting profile...
,D/BluetoothMapService( 5451): start()
,D/BluetoothMapService( 5451): mStartError = false
,D/BluetoothAdapterService( 5451): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67dae28
,D/HeadsetStateMachine( 5451): Try to query the phonestate on bind
,I/Telecom ( 1433): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1433): BluetoothPhoneService: handleMessage(7) / param 0
,I/Telecom ( 1433): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 1433): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,I/Telecom ( 1433): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,D/CommandListener(  280): Setting iface cfg
D/UserAnalysis.SecurePlaceDbHelper( 5492): SecurePlaceDbHelper() 
D/UserAnalysis( 5492): Create SecureDbHelper
D/CommandListener(  280): Trying to bring down wlan0
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,I/Telecom ( 1433): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128,
,E/WifiHW  ( 1020): supplicant_name : p2p_supplicant
,D/WifiMonitor( 1020): startMonitoring(wlan0) with mConnected = false
,W/BluetoothHeadset( 1433): Proxy not attached to service
,D/HeadsetPhoneState( 5451): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
I/Telecom ( 1433): BluetoothPhoneService: Result of Message : true
D/HeadsetStateMachine( 5451): Disconnected process message: 11
I/BluetoothSAPServiceJni( 5451): classInitNative(L204): succeeds
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1181): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1181): Wifi onReceive(2)
,D/STATUSBAR-QSTileView( 1181): onStateChanged: Wi-Fi
,D/SapService( 5451): Received start request. Starting profile...
,D/SapService( 5451): start()
D/BluetoothSAPServiceJni( 5451): initializeNative(L209): sap
I/bluedroid( 5451): get_profile_interface sap
,D/SapService( 5451): mStartError = false
D/BluetoothAdapterService( 5451): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67dae28
D/HeadsetPhoneState( 5451): sendDeviceDataStateChanged
,D/HeadsetPhoneState( 5451): Signal level : previous=0 curr=0
,E/BluetoothAdapterService(108899880)( 5451): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp( 5451): Proxy object connected
D/BluetoothAdapterService( 5451): Bluetooth A2dp source service connected
E/BluetoothAdapterService(108899880)( 5451): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,D/HeadsetStateMachine( 5451): Disconnected process message: 18
D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/HeadsetPhoneState( 5451): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5451): Disconnected process message: 11
,D/HotspotTile( 1181): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1181): onReceive : 2, 0,
,D/IntelligenceServiceApplication( 5492): onCreate()
E/BluetoothAdapterService(108899880)( 5451): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(108899880)( 5451): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(108899880)( 5451): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,D/WifiCredService( 1296): Action received :android.net.wifi.WIFI_STATE_CHANGED
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5518): MountEmulatedStorage()
,E/Zygote  ( 5518): v2
D/IntelligenceServiceApplication( 5492): no applications having user consent for prediction
,I/libpersona( 5518): KNOX_SDCARD checking this for 10141
I/libpersona( 5518): KNOX_SDCARD not a persona
,I/SELinux ( 5518): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=5518 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 4856:com.wssyncmldm/1000 (adj 15): empty #31
,I/SELinux ( 5518): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5518): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetection::stopService] Service stopped.
I/wpa_supplicant( 5517): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 5517): Successfully initialized wpa_supplicant
,I/SecureStorage( 5517): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage( 5517): [INFO]: SPID(0x00000000)This device supports Secure Storage
,V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,I/SecureStorage(  348): [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 5517
I/SecureStorage(  348): [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
I/SecureStorage( 5517): [INFO]: SPID(0x00000000)SS Daemon is running
,I/wpa_supplicant( 5517): ssSupport state is = 1
,I/wpa_supplicant( 5517): >>>>> GET KEY, IV <<<<<
I/SecureStorage( 5517): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  348): [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 5517
I/SecureStorage(  348): [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
,D/TimaKeyStoreProvider( 5518): TimaSignature is unavailable
,D/ActivityThread( 5518): Added TimaKeyStore provider,
,W/ResourcesManager( 5518): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5518): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
W/ResourcesManager( 5518): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5518): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_4856/cgroup.procs: No such file or directory
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,I/PowerManagerService( 1020): [PWL] Off : 105s ago
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,E/BluetoothAdapterService(108899880)( 5451): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,E/BluetoothAdapterService(108899880)( 5451): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,D/AuthorizationBluetoothService( 1692): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager( 1020): Killing 4876:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,D/BluetoothAdapterState( 5451): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 5451): enable
,I/bt_hci_bdroid( 5451): init
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,I/bt_vendor( 5451): bt-vendor : init
I/bt_vendor( 5451): bt-vendor : get_bt_soc_type
E/bt_vendor( 5451): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 5451): init: Local BD Address : 41:75:50:a9:ec:08
D/bt_userial_mct( 5451): userial_init
I/GKI_LINUX( 5451): gki_task_entry task_id=0 [BTU] starting
,I/bt_vendor( 5451): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 5451): Starting hciattach daemon
I/bt_vendor( 5451): try to set false
,I/bt_vendor( 5451): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 5451): Starting hciattach daemon
I/bt_vendor( 5451): try to set true
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,I/qcom-bluetooth( 5548): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,I/SecureStorage(  348): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0,
,I/SecureStorage( 5517): [INFO]: SPID(0x00000001)Processing data has been completed,
,I/qcom-bluetooth( 5554): /system/etc/init.qcom.bt.sh: Transport : smd ,
,I/wpa_supplicant( 5517): Ctrl_iface: loading cred from phone,
I/SecureStorage( 5517): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
I/qcom-bluetooth( 5555): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/SecureStorage( 5517): [INFO]: SPID(0x00000001)This device supports Secure Storage,
I/SecureStorage(  348): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5517
I/SecureStorage(  348): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C,
,I/SecureStorage( 5517): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5517): ssSupport state is = 1
I/wpa_supplicant( 5517): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5517): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5517): SIM READ ERROR
I/wpa_supplicant( 5517): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5517): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5517): SIM READ ERROR
I/wpa_supplicant( 5517): Blacklist: Clear (all) 
I/wpa_supplicant( 5517): wpa_default_ap_write_once
I/wpa_supplicant( 5517): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5517): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant( 5517): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 5517): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5517): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
I/wpa_supplicant( 5517): rfkill: Cannot open RFKILL control device
I/qcom-bluetooth( 5558): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,I/qcom-bluetooth( 5559): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,I/qcom-bluetooth( 5560): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,I/qcom-bluetooth( 5561): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/wpa_supplicant( 5517): wlan0: Setting scan request: 0 sec 100000 usec
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 41895(2MB) AllocSpace objects, 33(528KB) LOS objects, 33% free, 23MB/35MB, paused 2.520ms total 195.044ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3406): Starting #2
,D/BadgeProvider( 5165): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/Hs20UtilService( 3406): Message received 5011
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5565): MountEmulatedStorage(),
E/Zygote  ( 5565): v2
I/libpersona( 5565): KNOX_SDCARD checking this for 1000
I/libpersona( 5565): KNOX_SDCARD not a persona
,I/SELinux ( 5565): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=5565 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 5565): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5565): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1020): failed to open /acct/uid_10139/pid_4876/cgroup.procs: No such file or directory
,I/wpa_supplicant( 5517): wlan0: State: DISCONNECTED -> DISCONNECTED
I/SecureStorage( 5517): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,D/BadgeProvider( 5165): sendNotify entered. [uri] : content://com.sec.badge/apps/1,
D/BadgeProvider( 5165): sendNotify, [notify] : null
D/BadgeProvider( 5165): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5165): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5165): update, [UpdateCount] : 1
D/Launcher.Model( 1478): reloadBadges entered.
D/TimaKeyStoreProvider( 5565): TimaSignature is unavailable
D/ActivityThread( 5565): Added TimaKeyStore provider
,I/SecureStorage( 5517): [INFO]: SPID(0x00000001)This device supports Secure Storage
,I/SecureStorage(  348): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5517
I/SecureStorage(  348): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5517): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5517): ssSupport state is = 1
,I/wpa_supplicant( 5517): Ctrl_iface: loading cred from phone
I/SecureStorage( 5517): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,I/SecureStorage( 5517): [INFO]: SPID(0x00000001)This device supports Secure Storage,
I/SecureStorage(  348): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5517
I/SecureStorage(  348): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5517): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5517): ssSupport state is = 1
I/wpa_supplicant( 5517): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant( 5517): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5517): SIM READ ERROR
I/wpa_supplicant( 5517): wpa_default_ap_write_once
,I/wpa_supplicant( 5517): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5517): rfkill: Cannot open RFKILL control device
,I/qcom-bluetooth( 5582): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:75:41 
,I/Nat464Xlat( 1020): interfaceLinkStateChanged p2p0, false
D/Tethering( 1020): interfaceLinkStateChanged p2p0, false
D/Tethering( 1020): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1020): interfaceLinkStateChanged p2p0, false
D/Tethering( 1020): interfaceLinkStateChanged p2p0, false
D/Tethering( 1020): interfaceStatusChanged p2p0, false
,I/qcom-bluetooth( 5583): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,D/SecurityLogAgent( 5565): KnoxConfiguration : Current State = 1,
,D/SecurityLogAgent( 5565): KnoxConfiguration : Current State Mapping Found ,
D/SecurityLogAgent( 5565): StateMachine : Current State = 1
,D/SecurityLogAgent( 5565): StateMachine : Changed Current State = 1
,I/ActivityManager( 1020): Killing 3758:com.google.android.talk/u0a102 (adj 15): empty #31
,I/bt_vendor( 5451): bluetooth satus is on
,D/bt_userial_mct( 5451): userial_open(port:0)
I/bt_vendor( 5451): bt-vendor : BT_VND_OP_USERIAL_OPEN
,I/bt_vendor( 5451): Done intiailizing UART
,I/bt_vendor( 5451): Done intiailizing UART
,I/bt_userial_mct( 5451): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
I/bt_vendor( 5451): Bluetooth Firmware and transport layer are initialized
,D/bt_userial_mct( 5451): Entering userial_read_thread()
,I/wpa_supplicant( 5517): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 5517): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/        ( 5451): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 5451): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5451): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5451): BTE_InitTraceLevels -- TRC_AVDT
,I/        ( 5451): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5451): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5451): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5451): BTE_InitTraceLevels -- TRC_BTM
,I/        ( 5451): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5451): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5451): BTE_InitTraceLevels -- TRC_SAP
I/        ( 5451): BTE_InitTraceLevels -- TRC_SDP
,I/        ( 5451): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5451): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5451): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5451): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 5451): BTE_InitTraceLevels -- TRC_PROTOCOL
,W/ActivityManager( 1020): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/wpa_supplicant( 5517): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant( 5517): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5517): Skip scan - bUseNetwork false
,E/WifiStateMachine( 1020): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative-wlan0( 1020): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 5517): HOTSPOT20_ENABLE called
I/wpa_supplicant( 5517): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5517): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5517): SIM READ ERROR
I/wpa_supplicant( 5517): Blacklist: Clear (all) 
,I/wpa_supplicant( 5517): wlan0: Setting scan request: 0 sec 0 usec,
,I/wpa_supplicant( 5517): Skip scan - bUseNetwork false
,D/WifiNative-wlan0( 1020): callSECApiInt - ID [210]
,D/WifiConfigStore( 1020): Loading config and enabling all networks 
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1181): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1181): Wifi onReceive(3)
,D/STATUSBAR-QSTileView( 1181): onStateChanged: Wi-Fi
,D/HotspotTile( 1181): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1181): onReceive : 3, 0
,W/bt-l2cap( 5451): l2c_link_processs_ble_num_bufs 16
,D/WifiCredService( 1296): Action received :android.net.wifi.WIFI_STATE_CHANGED
,W/libprocessgroup( 1020): failed to open /acct/uid_10102/pid_3758/cgroup.procs: No such file or directory
,E/bt-btm  ( 5451): BTM_SecRegister:p_cb_info->p_le_callback == 0xa43b3ead 
E/bt-btm  ( 5451): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa43b3ead 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3406): Starting #3
,I/Hs20UtilService( 3406): Message received 5011
,E/WifiConfigStore( 1020): Not a HS20
,E/WifiConfigStore( 1020): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/SecurityLogAgent( 5565): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5565): KnoxConfiguration : Current State Mapping Found 
D/WifiNative-wlan0( 1020): callSECApiInt - ID [65]
D/SecurityLogAgent( 5565): StateMachine : Current State = 1
D/SecurityLogAgent( 5565): StateMachine : Changed Current State = 1
,D/WifiNative-wlan0( 1020): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 5517): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 5517): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 5517): reset timer : RESET_TIMER 0
I/wpa_supplicant( 5517): P2P: Current p2p state = IDLE
I/wpa_supplicant( 5517): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 5517): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5517): First Scan Start
,I/wpa_supplicant( 5517): Scan requested (ret=0) - scan timeout 30 seconds
,I/Nat464Xlat( 1020): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1020): interfaceLinkStateChanged p2p0, false
D/WifiNative-wlan0( 1020): Setting external_sim to 1
D/Tethering( 1020): interfaceStatusChanged p2p0, false
,D/WifiStateMachine( 1020): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1020): startHal
E/wifi    ( 1020): getStaticLongField sWifiHalHandle 0x9d77088c
I/WifiNative-HAL( 1020): Could not start hal
,D/BluetoothAdapterProperties( 5451): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,E/WifiNative-wlan0( 1020): do suspend true
,E/WifiStateMachine( 1020): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiP2pService( 1020): P2pDisabledState{ what=131203 }
,D/WifiScanningService( 1020): SCAN_AVAILABLE : 3
,E/bt-btif ( 5451): Calling BTA_HhEnable
E/bt-btif ( 5451): BTM_SEC_REG[7x0002)
,D/BluetoothAdapterProperties( 5451): Address is:08:EC:A9:50:75:41
E/BluetoothServiceJni( 5451): populateRssiValuesNative
I/bluedroid( 5451): getModelRssiValues
E/BluetoothServiceJni( 5451): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5451): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/WifiScanningService( 1020): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService( 1020): SCAN_AVAILABLE : 3
,E/WifiStateMachine( 1020): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1020): callSECStringApiVoid - ID [215]
I/WifiNative-HAL( 1020): startHal
E/WifiNative-wlan0( 1020): invaild command id : 215
E/wifi    ( 1020): getStaticLongField sWifiHalHandle 0x9eaaa9bc
I/WifiNative-HAL( 1020): Could not start hal
E/WifiScanningService( 1020): could not start HAL
,E/WifiStateMachine( 1020): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1020): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1020): invaild command id : 215
,D/RttService( 1020): DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  280): Setting iface cfg
D/CommandListener(  280): Trying to bring up p2p0
,D/BluetoothAdapterProperties( 5451): Name is: A3-1
,D/WifiMonitor( 1020): startMonitoring(p2p0) with mConnected = true
,I/wpa_supplicant( 5517): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
D/WifiP2pService( 1020): P2pEnablingState
I/wpa_supplicant( 5517): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/WifiP2pService( 1020): P2pEnablingState{ what=147457 }
D/WifiP2pService( 1020): P2p socket connection successful
,D/WifiP2pService( 1020): P2pEnabledState
,E/wpa_supplicant( 5517): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine( 1020): Failed to set frequency band 0
D/SettingsProvider( 1020): name = bluetooth_name
,D/BluetoothAdapterProperties( 5451): Scan Mode:20
D/BluetoothAdapterProperties( 5451): Discoverable Timeout:120
D/BluetoothAdapterProperties( 5451): LE Address is:C8:D9:53:A0:EA:82
,E/bt-btif ( 5451): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 5451): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,E/bt_mct  ( 5451): hci lib postload completed
D/WifiP2pService( 1020): sending p2p connection changed broadcast: IDLE
,E/bt-btif ( 5451): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 5451): btif_sock_init: !vhci_init
D/IOP_DB_BT( 5451): db_open: file /etc/bluetooth/iop_bt.db
,E/WifiStateMachine( 1020): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
,D/WifiP2pService( 1020): create mNetworkAgent
,D/WifiDisplayController( 1020): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/IOP_DB_BT( 5451): db_open: db_open : handle 3027656720l, read 13894 bytes onto local cache
,D/IOP_DB_BT( 5451): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
,D/IOP_DB_BT( 5451): db_query: result 1
I/        ( 5451): iop_db_open: iop_db_open status 0
,D/bte_conf( 5451): Device ID record 1 : primary
D/bte_conf( 5451):   vendorId            = 0075
D/bte_conf( 5451):   vendorIdSource      = 0001
D/bte_conf( 5451):   product             = 0100
D/bte_conf( 5451):   version             = 0200
D/bte_conf( 5451):   clientExecutableURL = 
D/bte_conf( 5451):   serviceDescription  = 
D/bte_conf( 5451):   documentationURL    = 
D/bte_conf( 5451): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 5451): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterState( 5451): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 5451): ScanMode =  20
D/BluetoothAdapterProperties( 5451): State =  11
,D/SecContentProvider( 1020): uri = 3 selection = isDiscoverableEnabled
,D/WifiDisplayController( 1020): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1020): disconnect
D/WifiDisplayController( 1020): updateConnection
,D/WifiDisplayController( 1020): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/BluetoothAdapterProperties( 5451): Setting state to 12
I/BluetoothAdapterState( 5451): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterProperties( 5451): Scan Mode:21
D/BluetoothAdapterProperties( 5451): Discoverable Timeout:120
,D/SettingsProvider( 1020): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 1002
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1020): ret = -1
,D/AllShareCastTile( 1181): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 5451): Bluetooth PBAP supproted is true,
D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/BluetoothAdapterService( 5451): updateAdapterState state is 12
D/AllShareCastTile( 1181): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 5451): Autoconnection is available 
,D/BluetoothAdapterService( 5451): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 5451): starting service from this receiver
D/BluetoothAdapter( 1433): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1433): onBluetoothStateChange: Bluetooth is on
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothA2dp( 5451): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1181): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1181): onBluetoothStateChange: Bluetooth is on
,I/BluetoothAdapterState( 5451): Entering On State from state = 11
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/BluetoothA2dp( 1020): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1020): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1020): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 5400): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 5400): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 5451): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 5451): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1654): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1654): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1458): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1458): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1442): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1442): onBluetoothStateChange: Bluetooth is on
,W/InputMethodManagerService( 1020): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1020): [BT Setting State] State =12
I/InputMethodManagerService( 1020): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/ConnectivityService( 1020): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1020): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1020): updateNetworkInfo()
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/CSLegacyTypeTracker( 1020): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,I/BluetoothPbapService( 5451): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/BluetoothTile( 1181):  onBluetoothStateChange:
,D/BluetoothTile( 1181):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1181): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1181):  getBluetoothState : 12
,I/SamsungIME( 1781): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothTile( 1181):  handleUpdatestate:false name:null
,D/BluetoothHeadset( 1433): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2b83101e, true
,D/BluetoothHeadset( 1433): registerMessageListener
D/BluetoothTile( 1181):  handleUpdatestate:false name:null
,D/HeadsetService( 5451): registerMessageListener
,D/StatusBarManagerService( 1020): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/WifiNative-p2p0( 1020): p2pGetDeviceAddress
D/HeadsetService( 5451): registerMessageListener
,D/HeadsetStateMachine( 5451): Disconnected process message: 70
D/WifiNative-p2p0( 1020): p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
I/Telecom ( 1433): BluetoothPhoneService: handleMessage(7) / param null
I/Telecom ( 1433): BluetoothPhoneService: updateHeadsetWithCallState
D/HeadsetStateMachine( 5451): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@16ac6d91
,D/StatusBarManagerService( 1020): setIconVisibility slot=bluetooth visible=true
,D/WifiDisplayController( 1020): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PhoneStatusBar( 1181): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/WifiP2pService( 1020): DeviceAddress: 0a:75:42
,D/WifiDisplayController( 1020): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A3-1
D/WifiDisplayController( 1020):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiDisplayController( 1020):  primary type: 10-0050F204-5
D/WifiDisplayController( 1020):  secondary type: null
D/WifiDisplayController( 1020):  wps: 0
D/WifiDisplayController( 1020):  grpcapab: 0
D/WifiDisplayController( 1020):  devcapab: 0
D/WifiDisplayController( 1020):  status: 3
D/WifiDisplayController( 1020):  wfdInfo: null
D/WifiDisplayController( 1020):  groupownerAddress: null
D/WifiDisplayController( 1020):  GOdeviceName: null
D/WifiDisplayController( 1020):  interfaceAddress: 
D/WifiDisplayController( 1020):  SConnectInfo : null
D/BluetoothTile( 1181):  handleUpdatestate:false name:null
,I/Telecom ( 1433): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,I/Telecom ( 1433): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,I/Telecom ( 1433): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,I/BluetoothPbapService( 5451): Handler(): got msg=1
,D/HeadsetStateMachine( 5451): Disconnected process message: 9
D/SecContentProvider( 1020): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/HeadsetStateMachine( 5451): mNumActive: 0 mNumHeld: 0 mCallState: 6
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/audio_hw_primary(  285): adev_set_parameters: enter: A2dpSuspended=false
,V/voice   (  285): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  285): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  285): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  285): platform_set_parameters: exit with code(-2)
,D/audio_hw_hfp(  285): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  285): adev_set_parameters: exit
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
E/HeadsetStateMachine( 5451): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/LocalBluetoothProfileManager( 1296): Adding local A2DP profile
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1296): Adding local HEADSET profile
,E/BluetoothHeadset( 1296): BTStateChangeCB is registed
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 1296): BluetoothHeadset service is binded
,D/BluetoothMap( 1296): Create BluetoothMap proxy object
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,V/BluetoothPbapService( 5451): PBAP Service initSocket try: 0
,D/WifiP2pService( 1020): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 1020): InactiveState
,D/WifiP2pService( 1020): InactiveState{ what=143376 }
,D/WifiP2pService( 1020): P2pEnabledState{ what=143376 }
,I/wpa_supplicant( 5517): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
E/ConnectivityService( 1020): updateNetworkInfo()
,D/WifiP2pService( 1020): InactiveState{ what=143376 }
,D/WifiP2pService( 1020): P2pEnabledState{ what=143376 }
D/BluetoothMapMasInstance( 5451): set MAP SDP message type : 1
,W/BluetoothAdapter( 5451): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5451): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 5451): bindListen(), new LocalSocket 
D/BluetoothSocket( 5451): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5451): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36c27a82
,D/BluetoothSocket( 5451): channel: 19
D/BluetoothPbapService( 5451): PBAP Socket is BluetoothServerSocket
,W/BluetoothAdapter( 5451): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5451): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
,D/BluetoothSocket( 5451): bindListen(), new LocalSocket 
D/BluetoothSocket( 5451): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5451): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@14adf593
,D/BluetoothSocket( 5451): channel: 5
,W/ContextImpl( 1296): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/Bluetoothsap( 1296): bindService called to Bluetooth SAP Service
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1296): PANU : true
,W/LocalBluetoothProfileManager( 1296): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 1296): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1296): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1296): onReceive
,D/BluetoothA2dp( 1296): Proxy object connected
,D/A2dpProfile( 1296): Bluetooth service connected
,V/BluetoothStatusReceiver( 1181): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1181): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,D/HeadsetProfile( 1296): Bluetooth service connected
,D/BluetoothAdapterService( 5451): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@67dae28
,D/BtConfig.SecureMode( 5451): isSecureModeOn:false
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothMap( 1296): Proxy object connected
D/MapProfile( 1296): Bluetooth service connected
D/BluetoothMap( 1296): getConnectedDevices()
,D/BluetoothPbap( 1296): Proxy object connected
,D/PbapServerProfile( 1296): Bluetooth service connected
D/Bluetoothsap( 1296): BluetoothSAP Proxy object connected
D/SapProfile( 1296): Bluetooth service connected
D/Bluetoothsap( 1296): getConnectedDevices()
,D/AuthorizationBluetoothService( 1692): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothInputDevice( 1296): Proxy object connected
D/HidProfile( 1296): Bluetooth service connected
,D/BluetoothPan( 1296): BluetoothPAN Proxy object connected
D/PanProfile( 1296): Bluetooth service connected
,E/SMD     (  290): DCD OFF
,D/SecContentProvider( 1020): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/NearbySettings( 1296): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1296): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1296): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1296): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1296): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1296): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1296): MountReceiver.mPrefHandler - 7002
W/BluetoothAdapter( 5451): getBluetoothService() called with no BluetoothManagerCallback
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5607): MountEmulatedStorage()
,E/Zygote  ( 5607): v2
I/libpersona( 5607): KNOX_SDCARD checking this for 10064
I/libpersona( 5607): KNOX_SDCARD not a persona
,I/SELinux ( 5607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=5607 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/BluetoothSocket( 5451): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
D/BluetoothSocket( 5451): bindListen(), new LocalSocket 
D/BluetoothSocket( 5451): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5451): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@311bed85
D/BluetoothSocket( 5451): channel: 12
I/BtOppRfcommListener( 5451): Accept thread started.
,E/SELinux ( 5607): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  307): Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 615us total 20.643ms,
,D/TimaKeyStoreProvider( 5607): TimaSignature is unavailable
,D/ActivityThread( 5607): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 16.939ms
,W/ResourcesManager( 5607): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 16.591ms
,D/FileShare-Client( 5607): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Client( 5607): ClientBroadcastReceiver.onReceive - disconnected
,D/FileShare-Client( 5607): Outbound.stopDelayTimer - 
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5622): MountEmulatedStorage()
,E/Zygote  ( 5622): v2
I/libpersona( 5622): KNOX_SDCARD checking this for 10065
I/libpersona( 5622): KNOX_SDCARD not a persona
,I/SELinux ( 5622): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1020): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5622 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5622): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Killing 3945:com.sec.spp.push/u0a32 (adj 15): empty #31
,E/SELinux ( 5622): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5622): TimaSignature is unavailable
,D/ActivityThread( 5622): Added TimaKeyStore provider
,D/FileShare-Server( 5622): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 1020): Killing 4567:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,W/libprocessgroup( 1020): failed to open /acct/uid_10032/pid_3945/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10032/pid_4567/cgroup.procs: No such file or directory
,I/wpa_supplicant( 5517): nl80211: Received scan results (8 BSSes),
I/wpa_supplicant( 5517): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 5517): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 5517): Trying to associate with  'G700'
I/wpa_supplicant( 5517): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 5517): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,D/WifiMonitor( 1020): didn't find BSSID Trying to associate with SSID 'NG700'
,I/WifiNative-HAL( 1020): startHal
E/wifi    ( 1020): getStaticLongField sWifiHalHandle 0x9d7708ac
I/WifiNative-HAL( 1020): Could not start hal
,D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
,I/rmt_storage(  269): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb88227c8
I/rmt_storage(  269): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  269): wakelock acquired: 1, error no: 42
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1199430344)
,E/wpa_supplicant( 5517): Cmd 35605 not handled
,I/wpa_supplicant( 5517): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 5517): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 5517): Associated with C0.AA.48
I/wpa_supplicant( 5517): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5517): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 5517): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
,D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
,I/wpa_supplicant( 5517): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5517): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 5517): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 5517): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 5517): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5517): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 5517): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 5517): Blacklist: Clear (temp) 
I/wpa_supplicant( 5517): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, true
,D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
,D/Tethering( 1020): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1020): interfaceStatusChanged wlan0, true
,E/Tethering( 1020): No numeric data
,D/Tethering( 1020): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1020): clearTetheredNotification()
,I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, true
,D/NtpTrustedTime( 1020): forceRefresh() from cache miss
,D/Tethering( 1020): interfaceLinkStateChanged wlan0, true
D/Tethering( 1020): interfaceStatusChanged wlan0, true
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 1000
,D/HotspotTile( 1181): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1181): updateTetherState():false, false
D/WifiNative-wlan0( 1020): callSECApiVoid - ID [50]
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 1000
,E/WifiConfigStore( 1020): setLastSelectedConfiguration -1,
V/NetworkStats( 1020): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1020): forceRefresh Fail.
D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
V/NetworkStats( 1020): performPollLocked() took 2ms,
D/ConnectivityService( 1020): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1020): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1020): updateNetworkInfo()
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1199430344) wakelock released: 1, error no: 0
I/rmt_storage(  269): 
,I/rmt_storage(  269): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb88227c8
,D/NtpTrustedTime( 1020): forceRefresh() from cache miss
E/WifiConfigStore( 1020): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/NtpTrustedTime( 1020): forceRefresh Fail.
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3406): Starting #4
,I/Hs20UtilService( 3406): Message received 5007
D/NearbySettings( 1296): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1296): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1296): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1296): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1296): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1296): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1296): MountReceiver.mPrefHandler - 7002
E/WifiConfigStore( 1020): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  280): Setting iface cfg
,E/WifiStateMachine( 1020): Start Dhcp Watchdog 1
,D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiNative-wlan0( 1020): do suspend false
,D/WifiP2pService( 1020): InactiveState{ what=143375 }
,D/WifiP2pService( 1020): P2pEnabledState{ what=143375 }
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/dhcpcd  ( 5642): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5642): version 5.5.6 starting,
,E/dhcpcd  ( 5642): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5642): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 5642): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 5642): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 5642): bssid match
,I/dhcpcd  ( 5642): wlan0: rebinding lease of 192.168.1.132,
,I/dhcpcd  ( 5642): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,I/dhcpcd  ( 5642): wlan0: leased 192.168.1.132 for 86400 seconds,
,E/WifiNative-wlan0( 1020): do suspend true
,D/WifiP2pService( 1020): InactiveState{ what=143375 },
D/WifiP2pService( 1020): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1020): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,E/WifiStateMachine( 1020): VerifyingLinkState enter
,D/WifiNative-wlan0( 1020): callSECApiInt - ID [210]
,E/ConnectivityService( 1020): updateNetworkInfo()
,D/ConnectivityService( 1020): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1020): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 1020): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1020): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 1020): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1020): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1020): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,E/WifiStateMachine( 1020): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/Hs20UtilService( 3406): Starting #5
D/ConnectivityService( 1020): Adding Route [fe80::/64 -> :: wlan0] to network 502
,I/Hs20UtilService( 3406): Message received 5007
,D/ConnectivityService( 1020): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,D/ConnectivityService( 1020): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
,D/NearbySettings( 1296): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,E/ConnectivityService( 1020): Unexpected mtu value: 0, wlan0
I/NearbySettings( 1296): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 1020): Setting Dns servers for network 502 to [/192.168.1.1]
,D/ConnectivityService( 1020): LTETest block dns file not exists
,E/WifiStateMachine( 1020): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine( 1020): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService( 1020): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,E/ConnectivityService( 1020): updateNetworkInfo()
E/ConnectivityService( 1020): updateNetworkInfo()
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1020): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1020): rematching NetworkAgentInfo [WIFI () - 502]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/WifiTrafficPoller( 1020): evaluateTrafficStatsPolling
,D/ConnectivityService( 1020):    accepting network in place of null
,D/WIFI    ( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/ConnectivityService( 1020): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/WIFI_P2P( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1458): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true,
,D/TelephonyNetworkFactory( 1458): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/System.out( 1020): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1020): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1020): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1020): (HTTPLog)-Thread-173-585263026: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
E/CSLegacyTypeTracker( 1020): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
I/System.out( 1020): (HTTPLog)-Static: isSBSettingEnabled false
D/CSLegacyTypeTracker( 1020): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 1000
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1020): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1020): mBoosterFLAG : 0
I/WifiTrafficPoller( 1020): current booster mode : FullMode
D/WifiNative-wlan0( 1020): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/Tethering( 1020): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1020): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1020): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,V/NetworkStats( 1020): updateIfacesLocked()
V/NetworkStats( 1020): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1020): forceRefresh() from cache miss
,D/ConnectivityService( 1020): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 1000
,D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/NetworkStats( 1020): performPollLocked() took 5ms
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3406): Starting #6
,I/Hs20UtilService( 3406): Message received 5007
,D/NearbySettings( 1296): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1296): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1296): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1296): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1296): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1296): MountReceiver.onReceive - Keep current state
,D/StatusBar.NetworkController( 1181): EthernetConnected: false
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE,
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3406): Starting #7
,I/Hs20UtilService( 3406): Message received 5007
,D/NearbySettings( 1296): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1296): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1020): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1020): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1020): mCursor = null
,I/System.out( 1020): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NtpTrustedTime( 1020): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1451923494516 mCachedNtpElapsedRealtime : 159166 mCachedNtpCertainty : 24
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/SecContentProvider2( 1020): uri = 15 selection = getToastEnabledState
D/SecContentProvider2( 1020): mCursor = null
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/SecContentProvider2( 1020): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1020): mCursor = null
,V/NetworkStats( 1020): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 04 Jan 2016 16:04:54 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1451923494355], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1451923494341]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Validated
,D/ConnectivityService( 1020): Validated NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1020): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1020): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService( 1020): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524290
I/art     ( 1181): Background sticky concurrent mark sweep GC freed 14047(599KB) AllocSpace objects, 2(43KB) LOS objects, 4% free, 15MB/16MB, paused 17.998ms total 54.563ms
,D/StatusBar.NetworkController( 1181): EthernetConnected: false
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1020): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1020
,D/SRIB_DCS( 1181): log_dcs ThreadedRenderer::initialize entered! 
,D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1020): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/AlarmManagerService( 1020): Setting time of day to sec=1451923494
D/AlarmManagerService( 1020): Trying to open a file
,D/AlarmManagerService( 1020): File Open Success
D/AlarmManagerService( 1020): File Close Success
I/AlarmManagerService( 1020): DRM_TIME_PATH CHMOD 666 for resetState done 
,V/AlarmManager( 1020): waitForAlarm result :65536
W/AlarmManagerService( 1020): Unable to set rtc to 1451923494: Invalid argument
,D/WifiStateMachine( 1020): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,I/DowntimeConditions( 1020): android.intent.action.TIME_SET ignored because schedule turned off.
,I/PCWCLIENTTRACE_PushUtil( 5025): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5025): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5025): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5025): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_SET
,W/Settings( 1020): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/splitIntent( 1020): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1020): base  index=20, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$ActiveReceiver
I/splitIntent( 1020): other index=23, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/AlarmManager( 1020): waitForAlarm result :4
,V/AlarmManager( 1020): No more alarm at this time.nowELAPSED=159627 batch.start=160537
D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/DrmEventService( 1020):  no response from SecureClock 
,E/Zygote  ( 5683): MountEmulatedStorage()
,E/Zygote  ( 5683): v2
I/libpersona( 5683): KNOX_SDCARD checking this for 10108
I/libpersona( 5683): KNOX_SDCARD not a persona
,I/SELinux ( 5683): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5683): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5683): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5683 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/SettingsProvider( 1020): name = lockscreen_zoom_panning_effect
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10049
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5683): TimaSignature is unavailable
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,D/ActivityThread( 5683): Added TimaKeyStore provider
,D/KeyguardEffectViewUtil( 1181): isStrongPowerSavingMode() :false
,D/KeyguardEffectViewController( 1181): isPreloadedWallpaper=true
,I/GeometricMosaic_Keyguard( 1181): update
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/KeyguardEffectViewUtil( 1181): getCurrentWallpaper() mWallpaperPath :null
,E/Zygote  ( 5699): MountEmulatedStorage()
E/Zygote  ( 5699): v2
I/libpersona( 5699): KNOX_SDCARD checking this for 10071
I/libpersona( 5699): KNOX_SDCARD not a persona
,I/SELinux ( 5699): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=5699 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/SELinux ( 5699): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5699): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5699): TimaSignature is unavailable
,D/ActivityThread( 5699): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 1692): Using platform SSLCertificateSocketFactory
,I/ConfigFetchService( 1931): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigService( 1692): onCreate
,I/ConfigFetchService( 1931): running network task: configservice_periodic
,E/WakeLock( 1931): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1931): launchTask
,I/KeyguardEffectViewUtil( 1181): set current wallpaper info
,D/SettingsProvider( 1020): name = keyguard_current_wallpaper_type
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10049
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,I/MusicStore( 5683): Database version: 120,
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1020): name = keyguard_current_wallpaper_file_path
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10049
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,E/GpsLocationProvider( 1020): No APN found to select.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5683): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,D/SettingsProvider( 1020): name = keyguard_current_wallpaper_res_id
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10049
,D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5683): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5683): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,W/ResourcesManager( 5683): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5683): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.youtube
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,V/JNIHelp ( 5683): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager( 1020): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=5735 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/Zygote  ( 5735): MountEmulatedStorage(),
,E/Zygote  ( 5735): v2
I/libpersona( 5735): KNOX_SDCARD checking this for 10161,
I/libpersona( 5735): KNOX_SDCARD not a persona
I/SELinux ( 5735): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5735): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5735): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/TEST    ( 1181): run!!!
,I/GeometricMosaic_Renderer( 1181): setBackgroundBitmap
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text,
,D/TimaKeyStoreProvider( 5735): TimaSignature is unavailable,
,D/ActivityThread( 5735): Added TimaKeyStore provider
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,W/ActivityThread( 5683): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5683): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@637e563: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5683): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5683): GMSCore installation verified
,I/ConfigStore( 5683): Config Database version: 1
,D/KeyguardEffectViewController( 1181): isPreloadedWallpaper=true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 5699): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/Auth.Api.Credentials( 1931): [CredentialSyncAdapter] Unknown sync event.,
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/BooksApp( 5699): Created application version: 3.6.9 (30609)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/DriveInitializer( 1931): Background init thread started
,I/ConfigFetchService( 1931): service connected
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,D/ConfigFetchService( 1931): ConfigApi connection successful.
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 1931): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,W/ResourcesManager( 5735): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5735): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1020): getStreamVolume 3 index 70
,V/AlarmManager( 1020): waitForAlarm result :4
,I/MediaRouter( 5683): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/DriveInitializer( 1931): Awaiting to be initialized
,V/JNIHelp ( 5735): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/art     ( 1692): Explicit concurrent mark sweep GC freed 17456(1006KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 7MB/12MB, paused 1.039ms total 101.221ms
,V/MusicLeanback( 5683): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ActivityThread( 5735): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5735): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14d55e7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5735): Installed default security provider GmsCore_OpenSSL
,I/NetworkMonitor( 5683): type=WIFI subType= reason=null isConnected=true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 67476(3MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/35MB, paused 2.761ms total 205.776ms
,W/DriveInitializer( 1931): Background init thread ended
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor( 5683): type=WIFI subType= reason=null isConnected=true
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5780): MountEmulatedStorage(),
E/Zygote  ( 5780): v2
I/libpersona( 5780): KNOX_SDCARD checking this for 10001
I/libpersona( 5780): KNOX_SDCARD not a persona
,I/SELinux ( 5780): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=5780 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5780): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5780): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/BooksSync( 5699): Starting books sync for 61035162, extras: ade
,D/TimaKeyStoreProvider( 5780): TimaSignature is unavailable
,D/ActivityThread( 5780): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GHttpClientFactory( 5683): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 5683): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/art     ( 5735): Suspending all threads took: 6.179ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 5735): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5735): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/Zygote  ( 5808): MountEmulatedStorage(),
E/Zygote  ( 5808): v2
I/libpersona( 5808): KNOX_SDCARD checking this for 1000
I/libpersona( 5808): KNOX_SDCARD not a persona
,I/SELinux ( 5808): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5808): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5808): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=5808 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5808): TimaSignature is unavailable
,D/ActivityThread( 5808): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 5808): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/YouTube MDX( 5735): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,D/ConnectivityService( 1020): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524295
D/ConnectivityService( 1020): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524295
D/ConnectivityService( 1020): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 5699): (284) automatic index on view_volumes(volume_id)
,W/ContextImpl( 5735): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DIAGMON_AGENT( 5808): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 5808): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/login_manager
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/login_manager without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DIAGMON_AGENT( 5808): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 5808): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 5808): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 5808): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/BooksConfig( 5699): GmsCore Version = 7.8.99 (2134222-434)
,E/Auth.Api.Credentials( 1931): [SyncManager] Error during the sync.
E/Auth.Api.Credentials( 1931): com.google.android.gms.auth.ad: BadAuthentication
E/Auth.Api.Credentials( 1931): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/Auth.Api.Credentials( 1931): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/Auth.Api.Credentials( 1931): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/Auth.Api.Credentials( 1931): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/Auth.Api.Credentials( 1931): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/Auth.Api.Credentials( 1931): 	at com.google.android.gms.common.server.s.b(SourceFile:59)
E/Auth.Api.Credentials( 1931): 	at com.google.android.gms.common.server.s.a(SourceFile:294)
E/Auth.Api.Credentials( 1931): 	at com.google.android.gms.common.server.s.a(SourceFile:201)
E/Auth.Api.Credentials( 1931): 	at com.google.android.gms.auth.b.a.a(SourceFile:316)
E/Auth.Api.Credentials( 1931): 	at com.google.android.gms.auth.api.credentials.be.a.b.b(SourceFile:285)
E/Auth.Api.Credentials( 1931): 	at com.google.android.gms.auth.api.credentials.sync.c.a(SourceFile:384)
E/Auth.Api.Credentials( 1931): 	at com.google.android.gms.auth.api.credentials.sync.b.a(SourceFile:114)
E/Auth.Api.Credentials( 1931): 	at com.google.android.gms.auth.api.credentials.sync.a.a(SourceFile:131)
E/Auth.Api.Credentials( 1931): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
E/Auth.Api.Credentials( 1931): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/dex2oat ( 5834): ----------------------------------------------------
I/dex2oat ( 5834): <SS>: S T A R T I N G . . .
I/dex2oat ( 5834): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 5834): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads668578441.jar --oat-fd=37 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads668578441.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/WindowManager( 1020): showStatusBarByNotification() mOpenByNotification=false
,I/DBG_POLICYDM( 5061): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 1181): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1181): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5061): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5061): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5061): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,D/KnoxNotification( 1181): ----- inflateViews : modified publicViewLocal -----
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/KnoxNotification( 1181): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1181): PersonaID is invalid or persona doesn't exists. : 0,
,E/Zygote  ( 5852): MountEmulatedStorage()
E/Zygote  ( 5852): v2
I/libpersona( 5852): KNOX_SDCARD checking this for 10008
I/libpersona( 5852): KNOX_SDCARD not a persona
,I/SELinux ( 5852): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1020): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=5852 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5852): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5852): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PicasaService( 4326): start picasa sync
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PicasaService( 4326): end picasa sync
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5735): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5735): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5735): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/InstanceID/Rpc( 5735): Found 10011
D/TimaKeyStoreProvider( 5852): TimaSignature is unavailable
,D/ActivityThread( 5852): Added TimaKeyStore provider
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/BooksAccountManager( 5699): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5699): Soft error
E/BooksSync( 5699): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5699): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 5699): Sync error
E/BooksSync( 5699): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5699): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5699): Finished books sync
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 22220, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,I/dex2oat ( 5834): dex2oat took 285.871ms (threads: 4)
,W/ContextImpl( 5735): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1020): Killing 5006:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,I/ActivityManager( 1020): Killing 4974:com.samsung.helphub/1000 (adj 15): empty #32
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
,I/FOTA_Client( 5852): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/FOTA_Client( 5852): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/ActivityManager( 1020): Killing 4991:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3448): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 04 17:04:57 GMT+01:00 2016
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,D/Finsky  ( 4697): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4697): [1] 5.onFinished: Installation state replication failed.
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/Finsky  ( 4697): [1] 5.onFinished: Scheduling replication attempt 5.
,I/KLMS-2.5.123: ( 3448): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3448): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3448): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3448): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3448): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3448): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3448): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3448): StateImplV2(): networkChangeListener().START
,E/Zygote  ( 5899): MountEmulatedStorage()
E/Zygote  ( 5899): v2
I/libpersona( 5899): KNOX_SDCARD checking this for 10031
I/libpersona( 5899): KNOX_SDCARD not a persona
I/SELinux ( 5899): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1020): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=5899 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 5899): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5899): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3448): NetworkChangeOperations(): uploadRequestLog().START 
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3448): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3448): StateImplV2(): networkChangeListener().END
,D/TimaKeyStoreProvider( 5899): TimaSignature is unavailable
,D/ActivityThread( 5899): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3448): KLMSIntentService(): onDestroy()
,I/ActivityManager( 1020): Killing 4626:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_4974/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10087/pid_5006/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10014/pid_4991/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10029/pid_4626/cgroup.procs: No such file or directory
,W/BaseAppContext( 1931): Using Auth Proxy for data requests.
,W/BaseAppContext( 1931): Using Auth Proxy for data requests.
,W/BaseAppContext( 1931): Using Auth Proxy for data requests.
,I/System.out( 5735): Thread-1003(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5735): Thread-1003(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5735): Thread-1003(ApacheHTTPLog):isShipBuild true
,W/BaseAppContext( 1931): Using Auth Proxy for data requests.
,I/System.out( 5735): Thread-1003(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 5735): Thread-1003(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/AndroidHttpClient( 5735): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
,D/AndroidHttpClient( 5735): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 5735): Thread-1017(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5735): Thread-1017(ApacheHTTPLog):isShipBuild true
I/System.out( 5735): Thread-1017(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5735): Thread-1017(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/BaseAppContext( 1931): Using Auth Proxy for data requests.
,I/DBG_POLICYDM( 5061): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,W/BaseAppContext( 1931): Using Auth Proxy for data requests.
,W/BaseAppContext( 1931): Using Auth Proxy for data requests.
,I/DBG_POLICYDM( 5061): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5061): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5061): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,E/DBG_POLICYDM( 5061): [com.policydm.XDMBroadcastReceiver(240/xdmNotInitSetResume)] DM Not Init
,I/DBG_POLICYDM( 5061): [com.policydm.XDMApplication(246/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_POLICYDM( 5061): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 5061): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10161
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10161
,I/DBG_POLICYDM( 5061): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 5061): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 5061): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,I/SA      ( 5115): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5115): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 5115): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/qtaguid ( 5735): Tagging socket 54 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 5735, getuid(): 10161
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,I/SA      ( 5115): [SLFUCHKMGR] constructor called
,I/SA      ( 5115): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5115): [OR] == isSIMCardReady false ==
,I/SA      ( 5115): [SCU] == networkStateCheck == true
,I/SA      ( 5115): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5115): isChinaCountryCode : false
I/SA      ( 5115): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5115): [OR] == networkStateCheck true ==
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/dhcpcd  ( 5642): wlan0: sending IPv6 Router Solicitation
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 5061): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,I/SA      ( 5115): [OR] GetMyCountryZoneTask
,I/SA      ( 5115): [OR] onReceive END
,I/ActivityManager( 1020): Killing 5072:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,V/DownloadManager( 1227): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2015/12/31/12:24:10
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/01/04/17:04:57
,I/DBG_POLICYDM( 5061): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingAgent(324/xpollingDefaultPollingTime)] 
,D/accuweather( 1566): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1603): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,I/DBG_POLICYDM( 5061): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,D/accuweather( 1566): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1566): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1566): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1566): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5061): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingAgent(348/xpollingDefaultPollingTime)] Next Polling Time:2016/01/05/22:52:44
,D/SecContentProvider2( 1020): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1020): mCursor = null
I/DBG_POLICYDM( 5061): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 5061): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/SA      ( 5115): [SRS] prepareGetMyCountryZone
,I/DBG_POLICYDM( 5061): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 5061): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
I/DBG_POLICYDM( 5061): [com.policydm.restclient.XRCProcess(922/xspdHandler)] XEVENT_RC_GET_VERSION
,I/DBG_POLICYDM( 5061): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/DBG_POLICYDM( 5061): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5061): [com.policydm.restclient.XRCProcess(186/callRestClientThread)] szReqURL = http://svc-cf.spd.samsungdm.com/SM-A300FU/XEO/version.xml
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,W/libprocessgroup( 1020): failed to open /acct/uid_10148/pid_5072/cgroup.procs: No such file or directory
I/SA      ( 5115): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5115): [SSP] query invoked
,I/DBG_POLICYDM( 5061): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBSpdAdp(159/xdbSetSpdState)] nRestClientMode = 6
,E/DBG_POLICYDM( 5061): [com.policydm.restclient.XRCProcess(213/RestClientProcess)] SPD SERVICE Start!!
I/DBG_POLICYDM( 5061): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,W/ContextImpl( 5061): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.policydm.restclient.XRCProcess.RestClientProcess:214 com.policydm.restclient.XRCProcess.access$100:78 com.policydm.restclient.XRCProcess$RestClientThread.run:135 
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,I/art     ( 1692): Explicit concurrent mark sweep GC freed 13040(723KB) AllocSpace objects, 3(60KB) LOS objects, 39% free, 7MB/12MB, paused 996us total 219.575ms
,I/art     ( 1931): Explicit concurrent mark sweep GC freed 9846(860KB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 11MB/18MB, paused 1.365ms total 263.461ms
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 33555(1555KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 14.268ms total 214.844ms
,I/SurfaceFlinger(  259): id=13 Removed Uoast (8/9)
,I/SurfaceFlinger(  259): id=13 Removed Uoast (-2/9)
,D/accuweather( 1566): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1566): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.policydm, destAppInfo.processName = com.policydm
,I/SA      ( 5115): [TPMU] GetMccFromDB : null
,I/SA      ( 5115): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5115): [TPM] isNoProxy(default) : true
,D/PowerManagerService( 1020): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1020) eventTime = 162854
D/PowerManagerService( 1020): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1020 (0x0)
D/PowerManagerService( 1020): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1020, ws=WorkSource{10049}) (elapsedTime=3607)
,I/DBG_POLICYDM( 5061): [com.policydm.restclient.XRCProcess(623/execute)] 
,I/DBG_POLICYDM( 5061): [com.policydm.XDMService(61/onCreate)] 
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5061): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5061): [com.policydm.restclient.XRCProcess(1099/getPacket)] 
I/DBG_POLICYDM( 5061): -----------Device RestClient request-----------
I/DBG_POLICYDM( 5061): GET http://svc-cf.spd.samsungdm.com/SM-A300FU/XEO/version.xml HTTP/1.1
I/DBG_POLICYDM( 5061): User-Agent: samsung SM-A300FU SyncML_DM Client
I/DBG_POLICYDM( 5061): Connection: Keep-Alive
I/DBG_POLICYDM( 5061): Content-Type: application/xml
I/DBG_POLICYDM( 5061): Accept: application/xml
I/DBG_POLICYDM( 5061): ---------------- End ----------------
,I/DBG_POLICYDM( 5061): [com.policydm.XDMService(83/onStartCommand)] 
,E/Zygote  ( 5938): MountEmulatedStorage(),
E/Zygote  ( 5938): v2
I/libpersona( 5938): KNOX_SDCARD checking this for 10121
I/libpersona( 5938): KNOX_SDCARD not a persona
I/SELinux ( 5938): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=5938 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 5938): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5938): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityThread( 5061): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,D/TimaKeyStoreProvider( 5938): TimaSignature is unavailable
D/ActivityThread( 5938): Added TimaKeyStore provider
,I/System.out( 5061): Thread-854(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5061): Thread-854(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5061): Thread-854(ApacheHTTPLog):isShipBuild true
,I/System.out( 5061): Thread-854(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5061): Thread-854(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/File    ( 5115): fail readDirectory() errno=2
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 1000
,W/ResourcesManager( 5938): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5938): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5938): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/btif_config_util( 5451): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/System.out( 5735): Thread-1017 calls detatch()
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/QuickConnect( 5938): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,E/Zygote  ( 5955): MountEmulatedStorage()
E/Zygote  ( 5955): v2
I/libpersona( 5955): KNOX_SDCARD checking this for 10099
I/libpersona( 5955): KNOX_SDCARD not a persona
I/SELinux ( 5955): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=5955 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5955): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5955): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/QuickConnect( 5938): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 5938): PeriphStartReceiver.onReceive - no need to start
,D/TimaKeyStoreProvider( 5955): TimaSignature is unavailable
,D/ActivityThread( 5955): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5061): [com.policydm.restclient.XRCProcess(1099/getPacket)] 
I/DBG_POLICYDM( 5061): -----------Device RestClient response-----------
I/DBG_POLICYDM( 5061): Content-Type: application/xml
I/DBG_POLICYDM( 5061): Content-Length: 571
I/DBG_POLICYDM( 5061): Connection: keep-alive
I/DBG_POLICYDM( 5061): Date: Tue, 08 Dec 2015 03:49:13 GMT
I/DBG_POLICYDM( 5061): Last-Modified: Tue, 17 Nov 2015 07:32:13 GMT
I/DBG_POLICYDM( 5061): ETag: "4e5993ec21b533d31867dafe555308e7"
I/DBG_POLICYDM( 5061): Accept-Ranges: bytes
I/DBG_POLICYDM( 5061): Server: AmazonS3
I/DBG_POLICYDM( 5061): Age: 4557
I/DBG_POLICYDM( 5061): X-Cache: Hit from cloudfront
I/DBG_POLICYDM( 5061): Via: 1.1 3ba457b8dbcd42a85d6e93515e26caad.cloudfront.net (CloudFront)
I/DBG_POLICYDM( 5061): X-Amz-Cf-Id: cH9ECTff0FZdORTgWUofEKDvD5Z_5TXwCV-UNEMgsiAO1yCg5zw8Gw==
I/DBG_POLICYDM( 5061): ---------------- End ----------------
,I/System.out( 5061): Thread-854 calls detatch()
,I/DBG_POLICYDM( 5061): [com.policydm.restclient.XRCProcess(329/RestClientProcess)] HTTP status is 200
,I/DBG_POLICYDM( 5061): [com.policydm.adapter.XSPDAdapter(287/xspdGetLatestPolicyVersion)] systemPolicyVer = SEPF_SM-A300FU_5.0.2_0011
,I/qtaguid ( 5735): Untagging socket 54
,I/System.out( 5735): Thread-1003 calls detatch()
,I/DBG_POLICYDM( 5061): [com.policydm.adapter.XSPDAdapter(288/xspdGetLatestPolicyVersion)] spotaPolicyVer = SEPF_SM-A300FU_5.0.2_0027
,I/DBG_POLICYDM( 5061): [com.policydm.adapter.XSPDAdapter(320/xspdGetLatestPolicyVersion)] latestPolicyVer = SEPF_SM-A300FU_5.0.2_0027
,I/System.out( 5735): Thread-1005(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5735): Thread-1005(ApacheHTTPLog):isShipBuild true
I/System.out( 5735): Thread-1005(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5735): Thread-1005(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10161
I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingXml(98/getParsingVersionInfo)] androidver : 5.0.2
,I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingXml(99/getParsingVersionInfo)] policyver : SEPF_SM-A300FU_5.0.2_0027,
,I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingXml(98/getParsingVersionInfo)] androidver : 5.0.2-1
,I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingXml(99/getParsingVersionInfo)] policyver : SEPF_SM-A300FU_5.0.2-1_0038
,I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingXml(136/getParsingVersionInfo)] periodunit day,
,I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingXml(137/getParsingVersionInfo)] period 7
,I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingXml(138/getParsingVersionInfo)] time 9
,I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingXml(139/getParsingVersionInfo)] range 9
,I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingXml(140/getParsingVersionInfo)] reportperiod 14
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,I/qtaguid ( 5735): Tagging socket 47 with tag 0{0,0} for uid -1, pid: 5735, getuid(): 10161
,I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingXml(141/getParsingVersionInfo)] rReporttime 0
,I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingXml(142/getParsingVersionInfo)] reportrange 9
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 5565): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5565): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5565): StateMachine : Current State = 1
,D/SecurityLogAgent( 5565): StateMachine : Changed Current State = 1
,I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingAgent(205/xpollingNextPollingTime)] Next Polling Time:2016/01/11/17:02:03
,I/DBG_POLICYDM( 5061): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 5061): [com.policydm.polling.XPollingAgent(166/xpollingSaveXMLData)] Next StatusReport Time:2016/01/07/21:30:18
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/DBG_POLICYDM( 5061): [com.policydm.restclient.XRCProcess(389/RestClientProcess)] bPolicyUpdate is false
,I/DBG_POLICYDM( 5061): [com.policydm.restclient.XRCProcess(949/callRestClientFinish)] 
,E/DBG_POLICYDM( 5061): [com.policydm.XDMBroadcastReceiver(540/xdmSetCheckedIntent)] b_AlreadyReceivedIntent : false
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBSpdAdp(159/xdbSetSpdState)] nRestClientMode = 0
,I/DBG_POLICYDM( 5061): [com.policydm.ui.XUIAdapter(32/xuiAdpGetUiMode)] nDmUiMode : 0
,E/DBG_POLICYDM( 5061): [com.policydm.restclient.XRCProcess(984/callRestClientFinish)] SPD SERVICE Stop!!
,W/ContextImpl( 5061): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.policydm.restclient.XRCProcess.callRestClientFinish:985 com.policydm.restclient.XRCProcess.RestClientProcess:505 com.policydm.restclient.XRCProcess.access$100:78 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GHttpClientFactory( 5683): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.policydm, destAppInfo.processName = com.policydm
,I/CheckinService( 1931): Checking schedule, now: 1451923498608 next: 1451862150461
I/CheckinService( 1931): active receiver: enabled
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
I/DBG_POLICYDM( 5061): [com.policydm.XDMService(44/onDestroy)] 
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 5683): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/CheckinService( 1931): Preparing to send checkin request
,I/EventLogService( 1931): Accumulating logs since 1451923404118
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,I/MusicLifecycle( 5683): Sync started
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 5735): Untagging socket 47
,I/System.out( 5735): Thread-1005 calls detatch()
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GcmGroups( 1931): Failed to subscribe to group.
I/GcmGroups( 1931): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 1931): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 1931): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 1931): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 1931): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 1931): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 1931): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 1931): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 1931): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 1931): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 1931): 	at android.os.Looper.loop(Looper.java:145)
I/GcmGroups( 1931): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/GcmGroups( 1931): Groups upload failed, retrying in 24000:00:00
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/iu.SyncManager( 1931): SYNC; picasa accounts
,I/ActivityManager( 1020): Killing 5099:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,I/CheckinRequestBuilder( 1931): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1931): Failed to find provider info for com.google.android.wearable.settings
,W/libprocessgroup( 1020): failed to open /acct/uid_10152/pid_5099/cgroup.procs: No such file or directory
,I/Gmail   ( 5955): getAccountsCursor
,W/GAV2    ( 5955): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/NetworkLogImpl( 1931): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1931): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/iu.UploadsManager( 1931): num queued entries: 0
,I/iu.UploadsManager( 1931): num updated entries: 0
,I/iu.SyncManager( 1931): NEXT; no task
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ChimeraCfgMgr( 1931): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.youtube
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5955): getAccountsCursor
,D/ChimeraCfgMgr( 1931): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/Gmail   ( 5955): Error finding the version of the Email provider.....
E/Gmail   ( 5955): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5955): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 5955): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5955): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5955): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5955): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5955): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 5955): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 5955): We do not support migrating this version of the Email provider.
,D/GCM     ( 1692): Connected
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6003): MountEmulatedStorage()
,E/Zygote  ( 6003): v2
I/libpersona( 6003): KNOX_SDCARD checking this for 10102
I/libpersona( 6003): KNOX_SDCARD not a persona
I/SELinux ( 6003): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6003): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6003): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6003 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/Gmail   ( 5955): Sync started for account: account:61035162
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  307): Explicit concurrent mark sweep GC freed 8694(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.093ms total 27.974ms
,D/TimaKeyStoreProvider( 6003): TimaSignature is unavailable
,D/ActivityThread( 6003): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 682us total 16.981ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 16.699ms
,D/GCM     ( 1692): Message class com.google.f.a.a.p
,W/ActivityManager( 1020): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 6003): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/System.out( 5735): Thread-1006(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5735): Thread-1006(ApacheHTTPLog):isShipBuild true
I/System.out( 5735): Thread-1006(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5735): Thread-1006(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5735): Tagging socket 47 with tag 0{0,0} for uid -1, pid: 5735, getuid(): 10161
,I/qtaguid ( 5735): Tagging socket 52 with tag 0{0,0} for uid -1, pid: 5735, getuid(): 10161
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 5955): Observing account changes for notifications
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/qtaguid ( 5735): Untagging socket 47
I/System.out( 5735): Thread-1006 calls detatch()
,W/Kids    ( 1931): [AccountUtils] Account not ready
W/Kids    ( 1931): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1931): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1931): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1931): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1931): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1931): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1931): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1931): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1931): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1931): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1931): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1931): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 5955): (283) recovered 101 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
,D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
,D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.youtube
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/System.out( 5735): Thread-1007(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5735): Thread-1007(ApacheHTTPLog):isShipBuild true
I/System.out( 5735): Thread-1007(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5735): Thread-1007(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/qtaguid ( 5735): Tagging socket 47 with tag 0{0,0} for uid -1, pid: 5735, getuid(): 10161
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5735): Untagging socket 47
I/System.out( 5735): Thread-1007 calls detatch()
,E/File    ( 5955): fail readDirectory() errno=2
,I/Gmail   ( 5955): notifyAccountChanged
,I/Gmail   ( 5955): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5955): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5955): getAccountsCursor
,I/Gmail   ( 5955): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 18832(848KB) AllocSpace objects, 2(36KB) LOS objects, 33% free, 23MB/35MB, paused 2.915ms total 164.620ms
,I/Gmail   ( 5955): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/CheckinRequestBuilder( 1931): awaiting user notification for token
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
D/PanelView( 1181): There is/are notification(s) 
,D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.youtube
,I/Gmail   ( 5955): notifyAccountChanged
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/Babel_SMS( 6003): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6003): MmsConfig.loadMmsSettings
I/Babel_SMS( 6003): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel_SMS( 6003): MmsConfig.loadFromDatabase
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:461)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,E/Babel_SMS( 6003): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6003): MmsConfig.loadFromResources
,E/Babel_SMS( 6003): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6003): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6042): MountEmulatedStorage()
E/Zygote  ( 6042): v2
I/libpersona( 6042): KNOX_SDCARD checking this for 10011
I/libpersona( 6042): KNOX_SDCARD not a persona
,I/SELinux ( 6042): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6042): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1020): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6042 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
E/SELinux ( 6042): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/MusicLifecycle( 5683): Sync ended
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/MusicSyncAdapter( 5683): Sync failed due to an authentication issue.
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/QCamera2Factory(  285): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  285): getCameraInfo: X
,D/TimaKeyStoreProvider( 6042): TimaSignature is unavailable,
D/ActivityThread( 6042): Added TimaKeyStore provider
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 22248, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,W/QCamera2Factory(  285): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  285): getCameraInfo: X
,D/SyncManager( 1020): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 197152, reason: Periodic
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager( 1020): Killing 3211:com.google.android.gms.wearable/u0a11 (adj 15): empty #31
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6042): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6042): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5025): mConnectivityHandler : connected
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1020): waitForAlarm result :8
,W/Settings( 6003): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,I/Babel_Crash( 6003): startup - clean
,W/PCWCLIENTTRACE_AccountUtil( 5025): [hasSamungAccount] - No Samsung Account
,I/MultiDex( 6042): VM with version 2.1.0 has multidex support
I/MultiDex( 6042): install
I/MultiDex( 6042): VM has multidex support, MultiDex support library is disabled.
,D/ChimeraCfgMgr( 1931): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/Ads     ( 1931): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,W/libprocessgroup( 1020): failed to open /acct/uid_10011/pid_3211/cgroup.procs: No such file or directory
,V/JNIHelp ( 6042): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/art     ( 5115): Suspending all threads took: 19.852ms
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5025): [GetString-S]
,I/ReactiveServiceManager( 5025): Supported : 1
,D/QSEECOMAPI: ( 1020): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1020): App is not loaded in QSEE
,I/Babel   ( 6003): deleted: false for 0
,D/QSEECOMAPI: ( 1020): Loaded image: APP id = 9
,W/ActivityThread( 6042): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6042): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@311bed85: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6042): Installed default security provider GmsCore_OpenSSL
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/QSEECOMAPI: ( 1020): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1020): QSEECom_shutdown_app, app_id = 9
,E/terrier ( 1020): handleString: Failed to handle string(-4)
E/terrier ( 1020): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5025): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5025): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5025): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5025): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5025): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5025): [ensureRegistration] - No Samsung account
,I/art     ( 1692): Explicit concurrent mark sweep GC freed 32358(1719KB) AllocSpace objects, 10(194KB) LOS objects, 40% free, 7MB/12MB, paused 1.081ms total 138.073ms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=6066 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,E/Zygote  ( 6066): MountEmulatedStorage()
E/Zygote  ( 6066): v2
I/libpersona( 6066): KNOX_SDCARD checking this for 10087
I/libpersona( 6066): KNOX_SDCARD not a persona
,I/SELinux ( 6066): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/SELinux ( 6066): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6066): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6075): MountEmulatedStorage(),
E/Zygote  ( 6075): v2
I/libpersona( 6075): KNOX_SDCARD checking this for 10032
I/libpersona( 6075): KNOX_SDCARD not a persona
,I/SELinux ( 6075): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6075 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6075): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6075): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6066): TimaSignature is unavailable
,D/ActivityThread( 6066): Added TimaKeyStore provider
,W/VideoCapabilities( 6003): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6003): Unsupported mime audio/evrc
,W/AudioCapabilities( 6003): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6003): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6003): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6003): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6003): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6003): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6003): Unsupported mime audio/evrc
,W/VideoCapabilities( 6003): Unsupported mime video/wvc1
,D/TimaKeyStoreProvider( 6075): TimaSignature is unavailable
,D/ActivityThread( 6075): Added TimaKeyStore provider
,W/VideoCapabilities( 6003): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6003): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6003): Unsupported mime video/wvc1
,W/VideoCapabilities( 6003): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6003): Unsupported mime video/x-ms-wmv7
,I/SA      ( 5115): [RC New] Execute method=[GET] start
,D/WVCdm   (  285): Instantiating CDM.
,W/VideoCapabilities( 6003): Unsupported mime video/x-ms-wmv8
,I/WVCdm   (  285): CdmEngine::OpenSession
I/WVCdm   (  285): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  285): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/SA      ( 5115): [RC New] Security=[true]
,I/System.out( 5115): Thread-865(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables,
I/System.out( 5115): Thread-865(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5115): Thread-865(ApacheHTTPLog):isShipBuild true
I/System.out( 5115): Thread-865(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5115): Thread-865(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
W/VideoCapabilities( 6003): Unsupported mime video/mp43
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10036
,W/WVCdm   (  285): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,W/VideoCapabilities( 6003): Unsupported mime video/sorenson
,I/Gmail   ( 5955): getAccountsCursor
,W/VideoCapabilities( 6003): Unsupported mime video/mp4v-esdp
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SPPClientService( 6075): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6075): [PushClientApplication] Push log off : This is Ship build version
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/WVCdm   (  285): CdmEngine::QueryKeyControlInfo
,D/SPPClientService( 6075): PushLog.txt file is not deleted.
D/SPPClientService( 6075): PushLog.txt file is not deleted.
D/SPPClientService( 6075): ============PushLog. stop!
W/WVCdm   (  285): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  285): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  285): CdmEngine::GenerateKeyRequest
,I/GoogleURLConnFactory( 6042): Using platform SSLCertificateSocketFactory
,D/WVCdm   (  285): PrepareKeyRequest: nonce=1175435935
,E/SPPClientService( 6075): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6075): [SystemStateMoniter] Current Time : 165388
,I/GAV2    ( 5699): Thread[GAThread,5,main]: No campaign data found.
,I/VideoCapabilities( 6003): Unsupported profile 4 for video/mp4v-es
,E/SPPClientService( 6075): [SystemStateMoniter] No Connect : false
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 6042): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6042): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 6042): (HTTPLog)-Static: isShipBuild true
I/System.out( 6042): (HTTPLog)-Thread-1000-208619581: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 6042): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,I/System.out( 6042): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 6042): Tagging socket 30 with tag 180300000000{6147,0} for uid 10011, pid: 6042, getuid(): 10011
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6107 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 4961:com.android.mms/u0a41 (adj 15): empty #31
,E/Zygote  ( 6107): MountEmulatedStorage(),
E/Zygote  ( 6107): v2
I/libpersona( 6107): KNOX_SDCARD checking this for 10110
I/qtaguid ( 6042): Tagging socket 34 with tag 180300000000{6147,0} for uid 10011, pid: 6042, getuid(): 10011
,I/libpersona( 6107): KNOX_SDCARD not a persona
,I/SELinux ( 6107): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6107): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6107): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/VideoCapabilities( 6003): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6003): Unrecognized profile 2130706433 for video/avc
,D/TimaKeyStoreProvider( 6107): TimaSignature is unavailable
,D/ActivityThread( 6107): Added TimaKeyStore provider
,W/VideoCapabilities( 6003): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6003): Unrecognized profile 2130706433 for video/avc
,I/Gmail   ( 5955): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 5350, normalSync: true
,I/vclib   ( 6003): onServiceConnected
,W/Babel   ( 6003): Attempted to change video mute state without an active call.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/CountryDetector( 1020): No listener is left
,I/qtaguid ( 6042): Untagging socket 30
,W/libprocessgroup( 1020): failed to open /acct/uid_10041/pid_4961/cgroup.procs: No such file or directory
,I/System.out( 6003): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6003): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6003): (HTTPLog)-Static: isShipBuild true
I/System.out( 6003): (HTTPLog)-Thread-1006-306200823: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 6003): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10102
,I/DBG_POLICYDM( 5061): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/System.out( 6003): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/DBG_POLICYDM( 5061): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/GAv4    ( 6066): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6066):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6066):   adb logcat -s GAv4
,I/Babel   ( 6003): connection state changed from UNKNOWN to CONNECTED
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/ActivityManager( 1020): Killing 5146:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,W/GAv4    ( 6066): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,W/GAv4    ( 6066): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5061): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/DBG_POLICYDM( 5061): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,W/AnalyticsTrackerProxyImpl( 6066): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.33
,W/GAv4    ( 6066): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/DBG_POLICYDM( 5061): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5061): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,W/ResourcesManager( 5955): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5955): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SA      ( 5115): [RC New] [v2liruge] api execute + 914
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,I/SA      ( 5115): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5115): AsyncTask #1 calls detatch()
,W/libprocessgroup( 1020): failed to open /acct/uid_10042/pid_5146/cgroup.procs: No such file or directory
,I/SA      ( 5115): [ODM] saveOpenData( GEO_IP, PL )
,E/SMD     (  290): DCD OFF
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6066): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 6066): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6066): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SA      ( 5115): [OCP] update openData : PL
,V/JNIHelp ( 6066): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/SA      ( 5115): [TPMU] getNetworkMcc : 
,I/SA      ( 5115): [SCU] saveMccToPreferece Start
,V/JNIHelp ( 5955): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6066): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6066): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e9a9ddb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6066): Installed default security provider GmsCore_OpenSSL
,I/SA      ( 5115): [SCU] RegionMCC : 260
,I/SA      ( 5115): [SSP] query invoked
,I/SA      ( 5115): [TPMU] GetMccFromDB : null
I/SA      ( 5115): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5115): [SCU] saveMccToPreferece End
,I/SA      ( 5115): [RC New] executeRequest [v2liruge] end. 1243
,I/SA      ( 5115): [RC New] Execute end
,I/SA      ( 5115): [OR] GetMyCountryZoneTask mcc = 260,
,I/SA      ( 5115): [OR] GetMyCountryZoneTask Success
,W/ActivityThread( 5955): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5955): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e9a9ddb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5955): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6107): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/GAv4    ( 6107): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6107):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6107):   adb logcat -s GAv4
,I/dhcpcd  ( 5642): wlan0: sending IPv6 Router Solicitation
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4316, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:461)
,W/ContextImpl( 6107): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only,
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/dex2oat ( 6151): ----------------------------------------------------
,W/GAv4    ( 6107): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat ( 6151): <SS>: S T A R T I N G . . .
,I/dex2oat ( 6151): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 6151): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=40 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/GAv4    ( 6107): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6107): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 26609(1232KB) AllocSpace objects, 4(76KB) LOS objects, 33% free, 23MB/35MB, paused 2.666ms total 152.767ms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10087
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:461)
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6107): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6107): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/Gmail   ( 5955): notifyAccountChanged
,I/Gmail   ( 5955): getAccountsCursor
,I/dex2oat ( 6151): dex2oat took 192.165ms (threads: 4)
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/Adreno-EGL( 6042): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6042): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6042): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6042): Local Branch: 
I/Adreno-EGL( 6042): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6042): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6042):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5955): notifyAccountChanged
,W/Gmail   ( 5955): Sync complete for account: account:61035162
,I/Adreno-EGL( 6042): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6042): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6042): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6042): Local Branch: 
I/Adreno-EGL( 6042): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6042): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6042):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/ActivityManager( 1020): Killing 5165:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,I/Gmail   ( 5955): getAccountsCursor
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 22248, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1020): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 199979, reason: Periodic
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  285): CdmEngine::CloseSession
,I/WVCdm   (  285): L3 Terminate.
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
,I/WebViewFactory( 6107): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/LibraryLoader( 6107): Time to load native libraries: 2 ms (timestamps 7314-7316)
,I/LibraryLoader( 6107): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6107): Binding Chromium to main looper Looper (main, tid 1) {13c497a6}
,I/LibraryLoader( 6107): Expected native library version number "",actual native library version number ""
,I/chromium( 6107): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6107): Initializing chromium process, singleProcess=true
,W/art     ( 6107): Attempt to remove local handle scope entry from IRT, ignoring
,W/libprocessgroup( 1020): failed to open /acct/uid_10068/pid_5165/cgroup.procs: No such file or directory
,E/SysUtils( 6107): ApplicationContext is null in ApplicationStatus
,W/chromium( 6107): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6107): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6107): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6107): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6107): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6107): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6107): Local Branch: 
I/Adreno-EGL( 6107): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6107): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6107):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/Adreno-EGL( 6042): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6042): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6042): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6042): Local Branch: 
I/Adreno-EGL( 6042): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6042): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6042):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/chromium( 5400): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/AudioManagerAndroid( 6107): Requires BLUETOOTH permission
,I/NSApplication( 6107): Starting up...
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6197): MountEmulatedStorage()
,E/Zygote  ( 6197): v2
I/libpersona( 6197): KNOX_SDCARD checking this for 10077,
I/libpersona( 6197): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6197 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6197): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6197): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6197): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 6197): TimaSignature is unavailable
,D/ActivityThread( 6197): Added TimaKeyStore provider
,I/SyncAdapterService( 6107): Ignoring sync request for non-current account
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:461)
,E/DefaultHttpIssuer( 6066): Attempt to consume entity of HttpIssuer when no request is executing.
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,I/ActivityManager( 1020): Killing 5181:com.wsomacp/u0a23 (adj 15): empty #31
,E/DefaultHttpIssuer( 6066): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 6066): java.io.IOException
E/DefaultHttpIssuer( 6066): 	at cjw.b(PG:159)
E/DefaultHttpIssuer( 6066): 	at cju.b(PG:5072)
E/DefaultHttpIssuer( 6066): 	at dlh.b(PG:239)
E/DefaultHttpIssuer( 6066): 	at dlh.a(PG:140)
E/DefaultHttpIssuer( 6066): 	at dqo.a(PG:224)
E/DefaultHttpIssuer( 6066): 	at dlt.run(PG:9618)
E/DefaultHttpIssuer( 6066): 	at dlr.run(PG:3031)
,E/BaseSyncManager( 6066): AuthenticatorException
E/BaseSyncManager( 6066): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BaseSyncManager( 6066): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/BaseSyncManager( 6066): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BaseSyncManager( 6066): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/BaseSyncManager( 6066): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BaseSyncManager( 6066): 	at android.os.Binder.execTransact(Binder.java:461)
,W/libprocessgroup( 1020): failed to open /acct/uid_10023/pid_5181/cgroup.procs: No such file or directory
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/ActivityManager( 1020): Killing 5197:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/WVMDrmPlugIn(  284): WVMDrmPlugin::onInitialize : 3956
D/WVMDrmPlugIn(  284): WVMDrmPlugin::onSetOnInfoListener : add 3956
,D/WVMDrmPlugIn(  284): WVMDrmPlugin::onGetSupportInfo : 0
,I/WVCdm   (  285): CdmEngine::OpenSession
I/WVCdm   (  285): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  285): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/PeopleSync( 1931): onPerformSync() [5005f081]
,W/WVCdm   (  285): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup( 1020): failed to open /acct/uid_10048/pid_5197/cgroup.procs: No such file or directory
,I/WVCdm   (  285): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  285): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  285): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  285): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  285): PrepareKeyRequest: nonce=650003479
,D/WaitQueueForNetworkActivate( 5324): notifyNetworkActivated
,E/Watchdog( 1020): !@Sync 5
,W/ContextImpl( 5324): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1020): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,E/Auth.Api.Credentials( 1931): [CredentialSyncAdapter] Unknown sync event.
,I/GoogleURLConnFactory( 1931): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/PeopleSync( 1931): Setting subscription: result=true [5005f081]
I/PeopleSync( 1931): Starting sync, feed=null [5005f081]
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5324): AutoUpdateManager:IDLE:execute
,I/splitIntent( 1020): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
I/splitIntent( 1020): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,D/InitializeManagerStateMachine( 5324): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5324): exit::IDLE
D/InitializeManagerStateMachine( 5324): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5324): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5324): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5324): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5324): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5324): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5324): entry::SUCCESS
D/hcjo    ( 5324): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5324): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/FOTA_Client( 5852): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6234): MountEmulatedStorage()
,E/Zygote  ( 6234): v2
I/libpersona( 6234): KNOX_SDCARD checking this for 10058
I/libpersona( 6234): KNOX_SDCARD not a persona
I/SELinux ( 6234): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6234 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
I/SELinux ( 6234): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6234): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/FOTA_Client( 5852): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
,D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,I/Volley  ( 5324): RestApi Request Add : 2307
E/Zygote  ( 6243): MountEmulatedStorage()
E/Zygote  ( 6243): v2
I/libpersona( 6243): KNOX_SDCARD checking this for 10131
,I/libpersona( 6243): KNOX_SDCARD not a persona
,I/SELinux ( 6243): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,E/File    ( 5324): fail readDirectory() errno=2,
,I/SELinux ( 6243): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6243 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux ( 6243): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/SubscribedFeeds( 1931): Hard error
,D/TimaKeyStoreProvider( 6234): TimaSignature is unavailable
,D/ActivityThread( 6234): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/KLMS-2.5.123: ( 3448): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Mon Jan 04 17:05:03 GMT+01:00 2016
,D/daemonapp( 1603): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/daemonapp( 1603): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/TimaKeyStoreProvider( 6243): TimaSignature is unavailable
,D/ActivityThread( 6243): Added TimaKeyStore provider
,D/daemonapp( 1603): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/KLMS-2.5.123: ( 3448): KLMSAbstractReciever(): onReceive().END.
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/SA      ( 5115): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/daemonapp( 1603): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/KLMS-2.5.123: ( 3448): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3448): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/daemonapp( 1603): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/KLMS-2.5.123: ( 3448): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/daemonapp( 1603): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1603): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1603): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1603): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1603): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1603): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1603): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 22248, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1020): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 200523, reason: Periodic
,D/daemonapp( 1603): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1603): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1603): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1603): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1603): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/daemonapp( 1603): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3448): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
I/KLMS-2.5.123: ( 3448): KLMSIntentService(): TIME_CHANGED
,E/Zygote  ( 6266): MountEmulatedStorage(),
,I/KLMS-2.5.123: ( 3448): StateImplV2(): dateTimeChanged().START : Mon Jan 04 17:05:03 GMT+01:00 2016,
I/ActivityManager( 1020): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=6266 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/Zygote  ( 6266): v2
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
I/libpersona( 6266): KNOX_SDCARD checking this for 10041
I/libpersona( 6266): KNOX_SDCARD not a persona
I/SELinux ( 6266): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6266): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6266): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 6243): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6243): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6243): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,I/KLMS-2.5.123: ( 3448): StateImplV2(): dateTimeChanged().END
,I/KLMS-2.5.123: ( 3448): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6266): TimaSignature is unavailable
,D/ActivityThread( 6266): Added TimaKeyStore provider
,W/ResourcesManager( 6266): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6266): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6266): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6266): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6266): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/comdaemonstockapp( 1603): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1603): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/art     ( 5324): Suspending all threads took: 12.634ms
,I/ExternalOEMControlProvider( 6234): onCreate
,W/BaseAppContext( 1931): Using Auth Proxy for data requests.
,I/GAV2    ( 5955): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager( 1020): Killing 5220:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/accuweather( 1566): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,I/ Time Manager ( 6234): Time Difference not stored. TIME_DIFFERENCE
,D/accuweather( 1566): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6287 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Mms/MmsApp( 6266): [start]    onCreate() consume time = 0.0,
,E/Zygote  ( 6287): MountEmulatedStorage()
E/Zygote  ( 6287): v2
I/libpersona( 6287): KNOX_SDCARD checking this for 10081,
,I/libpersona( 6287): KNOX_SDCARD not a persona
,I/SELinux ( 6287): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6287): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6287): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/TimaKeyStoreProvider( 6287): TimaSignature is unavailable
,D/ActivityThread( 6287): Added TimaKeyStore provider
,D/daemonapp( 1603): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_5220/cgroup.procs: No such file or directory
,W/BaseAppContext( 1931): Using Auth Proxy for data requests.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6287): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6287): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6287): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6287): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6287): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/ActivityManager( 1020): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6308 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/Zygote  ( 6308): MountEmulatedStorage(),
E/Zygote  ( 6308): v2
I/libpersona( 6308): KNOX_SDCARD checking this for 10037
I/libpersona( 6308): KNOX_SDCARD not a persona
,I/SELinux ( 6308): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6308): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6308): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/SecurityLogAgent( 5565): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5565): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5565): StateMachine : Current State = 1
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6322): MountEmulatedStorage(),
E/Zygote  ( 6322): v2
I/libpersona( 6322): KNOX_SDCARD checking this for 10153
I/SELinux ( 6322): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/libpersona( 6322): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6322 uid=10153 gids={50153, 9997} abi=armeabi-v7a
,I/SELinux ( 6322): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6322): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850,
,D/TimaKeyStoreProvider( 6308): TimaSignature is unavailable,
,D/ActivityThread( 6308): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 6322): TimaSignature is unavailable
,D/ActivityThread( 6322): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 8676(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 40.994ms,
,W/BaseAppContext( 1931): Using Auth Proxy for data requests.,
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.866ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 815us total 16.894ms
,W/art     ( 6266): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 246.156ms
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 29065(1388KB) AllocSpace objects, 9(156KB) LOS objects, 33% free, 23MB/35MB, paused 2.786ms total 180.819ms
,I/PeopleSync( 1931): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1020): name = next_alarm_formatted
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
,D/SettingsProvider( 1020): selectionArgs: 10081
W/art     ( 6266): Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 151.181ms
,D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1020): ret = -1
,D/Mms/TelephonyPermission( 6266): start operation mode monitor
,D/Mms/ArtClassLoader( 6266): init before art
,W/ResourcesManager( 6308): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 6322): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6266): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission( 6266): DefaultSmsApp is com.android.mms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/Mms/TelephonyPermission( 6266): isDefault true
,D/Mms/MmsApp( 6266): onCreate() com.android.mms
,E/Zygote  ( 6340): MountEmulatedStorage()
E/Zygote  ( 6340): v2
I/libpersona( 6340): KNOX_SDCARD checking this for 1000
I/libpersona( 6340): KNOX_SDCARD not a persona
,I/SELinux ( 6340): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6340): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6340): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6340 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 5240:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6340): TimaSignature is unavailable
,D/ActivityThread( 6340): Added TimaKeyStore provider
,E/SMD     (  290): DCD OFF
,D/Mms/MmsApp( 6266): [start]    initCountryIso consume time = 510.815104
,D/CountryDetector( 1020): The first listener is added
,D/Mms/MmsApp( 6266): [end]    initCountryIso consume time = 27.293437
,D/Mms/MmsConfig( 6266): [start]    MmsConfig.init() consume time = 0.784792
,I/CalendarProvider2( 6308): CalendarProvider2.onCreate() called
,D/Mms/MmsConfig( 6266): before partial update
,W/art     ( 5324): Suspending all threads took: 8.967ms
,D/TimeService( 6340): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1451923504601
D/        ( 6340): TimeServiceNative: User Time to be set is 1451923504601
D/QC-time-services( 6340): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6340): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6340): Lib:time_genoff_operation: pargs->ts_val = 1451923504601
,D/QC-time-services( 6340): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  319): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  319): Daemon:Received base = 2, unit = 1, operation = 0,value = 1451923504601
D/QC-time-services(  319): Daemon:genoff_opr: Base = 2, val = 1451923504601, operation = 0
,D/QC-time-services(  319): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS6/1/70 9:50:22,
D/QC-time-services(  319): Daemon:Value read from RTC seconds = 15673822000,
D/QC-time-services(  319): Daemon:new time 1451923504601 
D/QC-time-services(  319): Daemon: delta 1436249682601 genoff 1436249682601 ,
D/QC-time-services(  319): Daemon:genoff_persistent_update: Writing genoff = 1436249682601 to memory
D/QC-time-services(  319): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  319): Daemon:time_persistent_memory_opr:Genoff write operation ,
,D/QC-time-services(  319): Updating the TOD offset
D/QC-time-services(  319): Daemon:genoff_persistent_update: Writing genoff = 1436249682601 to memory
D/QC-time-services(  319): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  319): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  319): Daemon:Update to modem bit set
E/QC-time-services( 6340): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  319): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  319): Daemon: Base = 2, Value being sent to MODEM = 1120284882601
I/ActivityManager( 1020): Killing 5258:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,E/QC-time-services(  319): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  319): Daemon: Time-services: Waiting to acceptconnection
,D/Mms/MmsConfig( 6266): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 6266): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 6266): isAuth is false
,D/Mms/MmsConfig( 6266): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1458): query,matched:2117, calling pid = 6266
,D/TP/MmsSmsProvider( 1458): match 2117:Elapsed time : 1.620 ms
,W/art     ( 6287): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 189.951ms
,D/EasySignUpManager_1.0.1( 6266): isAuth is false
,D/EasySignUpManager_1.0.1( 6266): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 6266): mps_code.dat does not exist
,E/CscParser( 6266): customer_path =/system/csc/customer.xml
,E/CscParser( 6266): fileName + /system/csc/customer.xml
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_5240/cgroup.procs: No such file or directory
,E/CscParser( 6266): mps_code.dat does not exist
,E/CscParser( 6266): customer_path =/system/csc/customer.xml
,E/CscParser( 6266): fileName + /system/csc/customer.xml
,D/CscParser( 6266): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 6266):  enable multiwindow = false
,E/Mms/MessageUtils( 6266): setCountryDetector : update country detector info 
,E/Mms/MessageUtils( 6266): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 6266): [end]    init() consume time = 175.054219
,D/Mms/Contact( 6266): [start]    init() consume time = 1.602448
,D/TP/MmsSmsProvider( 1458): query,matched:13, calling pid = 6266
,D/TP/MmsSmsProvider( 1458): match 13:Elapsed time : 1.612 ms
,D/Mms/Contact( 6266): [end]    init consume time = 14.644739
,I/art     ( 1692): Explicit concurrent mark sweep GC freed 15926(971KB) AllocSpace objects, 11(222KB) LOS objects, 39% free, 7MB/12MB, paused 1.072ms total 323.216ms
,D/Mms/DraftCache( 6266): [start]    rebuildCache consume time = 29.082292
,D/TP/MmsSmsProvider( 1458): query,matched:12, calling pid = 6266
,D/TP/MmsSmsProvider( 1458): match 12:Elapsed time : 1.589 ms
,W/libprocessgroup( 1020): failed to open /acct/uid_10098/pid_5258/cgroup.procs: No such file or directory
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6364 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a,
I/ActivityManager( 1020): Killing 5307:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #31
,E/Zygote  ( 6364): MountEmulatedStorage(),
E/Zygote  ( 6364): v2
,I/libpersona( 6364): KNOX_SDCARD checking this for 10090
I/libpersona( 6364): KNOX_SDCARD not a persona,
,I/SELinux ( 6364): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6364): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,D/Mms/DraftCache( 6266): [end]    rebuildCache consume time = 40.339427
,E/SELinux ( 6364): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/MethodReflector( 6266): getSubId is called
D/Mms/TelephonyUtils( 6266): getLongSubId from simSlot 0, return Value = -1
,D/Mms/ArtClassLoader( 6266): init [DONE] art
,D/Mms/MethodReflector( 6266): getTelephonyProperty is called
D/Mms/DownloadManager( 6266): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6266): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6266): auto download without roaming -> true
D/Mms/DownloadManager( 6266): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/MethodReflector( 6266): getSubId is called
,D/Mms/MethodReflector( 6266): getDefaultSmsSubId is called
D/TimaKeyStoreProvider( 6364): TimaSignature is unavailable
,D/ActivityThread( 6364): Added TimaKeyStore provider
,E/Mms/TelephonyUtils( 6266): subID is null or 0 length, so get DefaultSubId!!
,D/InitializeManagerStateMachine( 5324): exit::SUCCESS
D/InitializeManagerStateMachine( 5324): entry::IDLE
,D/Mms/TelephonyUtils( 6266): getLongSubId from simSlot 1, return Value = -1000
,D/Mms/MethodReflector( 6266): getTelephonyProperty is called
D/Mms/DownloadManager( 6266): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 6266): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 6266): auto download without roaming -> true
D/Mms/DownloadManager( 6266): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 6266): auto download during roaming secondary -> false
D/Mms/DownloadManager( 6266): mAutoDownload ------> true
,D/ComposerPerformance( 6266): 1451923504882 ms / [DONE] Composer constructor
,E/CII     ( 6266): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 6266): ReservationManager()
,I/Mms/ReservationManager( 6266): resetAfterConnected()
,D/TP/MmsSmsProvider( 1458): query,matched:7, calling pid = 6266
,D/TP/MmsSmsProvider( 1458): match 7:Elapsed time : 1.623 ms
,I/System.out( 5324): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 5324): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5324): (HTTPLog)-Static: isShipBuild true
I/System.out( 5324): (HTTPLog)-Thread-918-780348707: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5324): (HTTPLog)-Static: isSBSettingEnabled false
,I/Mms/ReservationManager( 6266): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/Conversation( 6266): [start]    init() consume time = 61.300312
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10009
,D/TP/MmsSmsProvider( 1458): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1458): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1458): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1458): sUpgradeVersion = 0, db.getVersion() = 81
,D/TP/MmsSmsProvider( 1458): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1458): need read changed broadcast:false
,D/Mms/Conversation( 6266): [end]    init consume time = 11.286771
,D/Mms/MessagingNotification( 6266): [start]    init() consume time = 1.644636
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/elm:15121( 6364): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15121( 6364): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6364): MDMBridge.setEnterpriseBridge()
,D/Mms/MessagingNotification( 6266): [end]    init consume time = 8.633906
,D/Mms/Synchronizer( 6266): [start]    doSync consume time = 1.970521
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/Mms/SpamFilter( 6266): [start]    SpamFilter fill() begin consume time = 2.620677
,D/elm:15121( 6364): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/TP/MmsSmsProvider( 1458): query,matched:0, calling pid = 6266
V/TP/MmsSmsProvider( 1458): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1458): match 0:Elapsed time : 1.303 ms
,D/TP/MmsSmsProvider( 1458): update, matched:300, calling pid = 6266
V/TP/MmsSmsProvider( 1458): syncDBData start
,D/TP/MmsSmsProvider( 1458): query,matched:400, calling pid = 6266
V/TP/MmsSmsProvider( 1458): syncDBData sms end
,V/TP/MmsSmsProvider( 1458): syncDBData mms end
D/elm:15121( 6364): ElmAgentService : onCreate()
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,V/TP/MmsSmsProvider( 1458): syncDBData end
,D/elm:15121( 6364): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:15121( 6364): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:15121( 6364): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:15121( 6364): ModuleBase.ModifySetAlarm()
D/elm:15121( 6364): MDMBridge.getInstance()
D/elm:15121( 6364): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 6391): MountEmulatedStorage()
E/Zygote  ( 6391): v2
I/libpersona( 6391): KNOX_SDCARD checking this for 10130
I/libpersona( 6391): KNOX_SDCARD not a persona
,I/SELinux ( 6391): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6391): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6391): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6391 uid=10130 gids={50130, 9997} abi=armeabi-v7a
D/Mms/MmsApp( 6266): [end]    onCreate() consume time = 35.719167
W/libprocessgroup( 1020): failed to open /acct/uid_10052/pid_5307/cgroup.procs: No such file or directory
D/Mms/DownloadManager( 6266): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 6266): roaming ------> false, mSimSlot = 0
,I/ActivityManager( 1020): Killing 4923:com.android.defcontainer/u0a3 (adj 15): empty #31
,D/Mms/Synchronizer( 6266): [end]    doSync consume time = 6.168802
,D/Mms/MethodReflector( 6266): getSubId is called
D/Mms/TelephonyUtils( 6266): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 6266): getTelephonyProperty is called
D/Mms/DownloadManager( 6266): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6266): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6266): auto download without roaming -> true
D/Mms/DownloadManager( 6266): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/DownloadManager( 6266): mAutoDownload ------> true
,I/WVCdm   (  285): CdmEngine::CloseSession
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/WVCdm   (  285): L3 Terminate.
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Zygote  ( 6407): MountEmulatedStorage()
E/Zygote  ( 6407): v2
I/libpersona( 6407): KNOX_SDCARD checking this for 10068
I/libpersona( 6407): KNOX_SDCARD not a persona
,I/SELinux ( 6407): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/TimaKeyStoreProvider( 6391): TimaSignature is unavailable
D/elm:15121( 6364): ElmAgentService : onDestroy().
D/ActivityThread( 6391): Added TimaKeyStore provider
,I/SELinux ( 6407): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6407): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6407 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 5492:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,D/Mms/SpamFilter( 6266): [end]    SpamFilter fill() finished consume time = 38.003437
,D/TimaKeyStoreProvider( 6407): TimaSignature is unavailable
,D/ActivityThread( 6407): Added TimaKeyStore provider
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1020): Killing 5607:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #31
,I/System.out( 5324): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 5324): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 5324, getuid(): 10009
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 6391): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/BadgeProvider( 6407): onCreate
D/BadgeProvider( 6407): DatabaseHelper
,I/CheckinRequestBuilder( 1931): Classify the device as Phone.
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6391): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Mms/MessagingNotification( 6266): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1458): query,matched:26, calling pid = 6266
,D/TP/SmsProvider( 1458): match 26:Elapsed time : 4.784 ms
,I/PeopleSync( 1931): Sync finished, successful=false, took 657ms
,I/splitIntent( 1020): Queue : backgroundsplit_0 intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1020): Killing 5622:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,D/TP/MmsSmsProvider( 1458): query,matched:6, calling pid = 6266
I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/TP/MmsSmsProvider( 1458): match 6:Elapsed time : 2.059 ms
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1020): failed to open /acct/uid_10003/pid_4923/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1020): failed to open /acct/uid_10064/pid_5607/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/libprocessgroup( 1020): failed to open /acct/uid_10055/pid_5492/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/qtaguid ( 5324): Untagging socket 26
,E/Zygote  ( 6428): MountEmulatedStorage()
,E/Zygote  ( 6428): v2
I/libpersona( 6428): KNOX_SDCARD checking this for 10023
I/libpersona( 6428): KNOX_SDCARD not a persona
,I/SELinux ( 6428): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6428): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6428 uid=10023 gids={50023, 9997} abi=armeabi-v7a
E/SELinux ( 6428): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1692): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/libprocessgroup( 1020): failed to open /acct/uid_10065/pid_5622/cgroup.procs: No such file or directory
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:461)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/ContactsSyncAdapter( 1692): innerSync failed
D/ContactsSyncAdapter( 1692): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1692): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 1692): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 1692): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 1692): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 1692): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 1692): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1692): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
D/ContactsSyncAdapter( 1692): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 1692): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
D/ContactsSyncAdapter( 1692): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 1692): 	at android.os.Binder.execTransact(Binder.java:461)
,D/hcjo    ( 5324): AutoUpdateTriggerManager:REQUEST2:setInterval:345600000
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
V/ConfigFetchTask( 1931): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1V9My0wVU_9JjDmpnpAL2FcC6tac2xBtP9ZpjgkeOkTaZpIn87uzVCFAg4qS4JlPOQxa8u8jbxN7OO5ry7zUBCMkCl_pdXSoHN31-hPUhdMGw5L42_bvFukXzkjEfsfP5X0DAQ6AiYcP3C3Xj6F6xUOMbG6L1NdnMs03Tgp5ojzXjZSrL8X1Xwb9X7c-8QXxqHk3lal
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
D/hcjo    ( 5324): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
D/hcjo    ( 5324): AutoUpdateManager:UPD_CHECK_TIMING:onUpdateTime
D/hcjo    ( 5324): SelfUpdateManager:IDLE:execute
D/TimaKeyStoreProvider( 6428): TimaSignature is unavailable
D/ActivityThread( 6428): Added TimaKeyStore provider
,D/hcjo    ( 5324): SelfUpdateManager:CONDITION_CHECK:onUpdateCondition
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,I/Volley  ( 5324): RestApi Request Add : 2346
,I/System.out( 5324): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5324): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 5324): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 5324, getuid(): 10009
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 22248, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1020): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 200643, reason: Periodic
,I/PeopleSync( 1931): Cannot authenticate [5005f081]
I/PeopleSync( 1931): com.google.android.gms.auth.ad: BadAuthentication
I/PeopleSync( 1931): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/PeopleSync( 1931): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/PeopleSync( 1931): 	at com.google.android.gms.auth.p.a(SourceFile:310)
I/PeopleSync( 1931): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
I/PeopleSync( 1931): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
I/PeopleSync( 1931): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
I/PeopleSync( 1931): 	at com.google.android.gms.people.service.g.b(SourceFile:171)
I/PeopleSync( 1931): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
I/PeopleSync( 1931): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
I/PeopleSync( 1931): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
I/PeopleSync( 1931): 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1184)
I/PeopleSync( 1931): 	at com.google.android.gms.people.sync.aa.g(SourceFile:1086)
I/PeopleSync( 1931): 	at com.google.android.gms.people.sync.aa.a(SourceFile:241)
I/PeopleSync( 1931): 	at com.google.android.gms.people.sync.s.a(SourceFile:283)
I/PeopleSync( 1931): 	at com.google.android.gms.people.sync.s.a(SourceFile:191)
I/PeopleSync( 1931): 	at com.google.android.gms.people.sync.s.a(SourceFile:93)
I/PeopleSync( 1931): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
I/PeopleSync( 1931): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
I/GoogleURLConnFactory( 1931): Using platform SSLCertificateSocketFactory
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6445): MountEmulatedStorage()
I/libpersona( 6445): KNOX_SDCARD checking this for 10100
E/Zygote  ( 6445): v2
I/libpersona( 6445): KNOX_SDCARD not a persona
I/SELinux ( 6445): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=6445 uid=10100 gids={50100, 9997, 3003} abi=armeabi-v7a
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 6445): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6445): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1020): Killing 5025:com.sec.pcw.device/1000 (adj 15): empty #31
,I/System.out( 1931): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,I/ActivityManager( 1020): Killing 4697:com.android.vending/u0a26 (adj 15): empty #31
,I/OMACP   ( 6428): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,D/TimaKeyStoreProvider( 6445): TimaSignature is unavailable
,D/ActivityThread( 6445): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/System.out( 1931): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1931): Tagging socket 107 with tag 40b00000000{1035,0} for uid -1, pid: 1931, getuid(): 10011
,W/libprocessgroup( 1020): failed to open /acct/uid_10026/pid_4697/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_5025/cgroup.procs: No such file or directory
,D/Mms/Omacp( 6266): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,I/OMACP   ( 6428): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 6428): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 6428): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 6428): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 6428): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 6428): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 6428): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 6428): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 6428): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 6428): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 6428): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false,
,I/OMACP   ( 6428): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 6428): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false,
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 1931): Tagging socket 120 with tag 40b00000000{1035,0} for uid -1, pid: 1931, getuid(): 10011
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/AbstractGoogleClient( 6445): Application name is not set. Call Builder#setApplicationName.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PeopleSync( 1931): ***Sync finished***, duration: 2289 [5005f081]
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 22248, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1020): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 200641, reason: Periodic
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5683): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
E/File    ( 5683): fail readDirectory() errno=2
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5683): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1020): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1020): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1020): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1692): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 1931): Untagging socket 107
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1692): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/System.out( 1931): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ConfigFetchTask( 1931): updating config table for com.google.android.gms
,I/System.out( 1931): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1931): Tagging socket 121 with tag 40800000000{1032,0} for uid -1, pid: 1931, getuid(): 10011
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/qtaguid ( 5324): Untagging socket -1
I/qtaguid ( 5324): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 5324): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger( 5324): untagSocket(-1) failed with errno -9
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1931): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/hcjo    ( 5324): SelfUpdateManager:REQUEST_UPD_CHECK:onUpdateCheckSuccessAndNoNeedUpdate
,D/hcjo    ( 5324): AutoUpdateManager:CHECK_SELF_UPD:onSelfUpdateResult:T
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/qtaguid ( 1931): Tagging socket 124 with tag 40800000000{1032,0} for uid -1, pid: 1931, getuid(): 10011
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/hcjo    ( 5324): SellerAppAutoUpdate:clearFlag
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SellerAppAutoUpdateManagerStateMachine( 5324): execute::IDLE:EXECUTE
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SellerAppAutoUpdateManagerStateMachine( 5324): exit::IDLE
D/SellerAppAutoUpdateManagerStateMachine( 5324): entry::TOKENCHECK
,D/SellerAppAutoUpdateManagerStateMachine( 5324): execute::TOKENCHECK:TOKEN_RECEIVED
W/ActivityManager( 1020): userId = 0, bbcId = -10000
D/SellerAppAutoUpdateManagerStateMachine( 5324): exit::TOKENCHECK
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
D/SellerAppAutoUpdateManagerStateMachine( 5324): entry::FAILED
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/hcjo    ( 5324): AutoUpdateManager:SELLER_UPD:onSellerAutoUpdateFailed
D/SellerAppAutoUpdateManagerStateMachine( 5324): exit::FAILED
D/SellerAppAutoUpdateManagerStateMachine( 5324): entry::IDLE
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6472): MountEmulatedStorage()
,E/Zygote  ( 6472): v2
I/libpersona( 6472): KNOX_SDCARD checking this for 10011
I/libpersona( 6472): KNOX_SDCARD not a persona
,I/SELinux ( 6472): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6472 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,I/SELinux ( 6472): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SELinux ( 6472): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/MusicLeanback( 5683): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 5683): Stop autocaching.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6472): TimaSignature is unavailable,
D/ActivityThread( 6472): Added TimaKeyStore provider,
,I/CheckinTask( 1931): Sending checkin request (9869 bytes),
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6488): MountEmulatedStorage()
,E/Zygote  ( 6488): v2
I/libpersona( 6488): KNOX_SDCARD checking this for 10026
I/libpersona( 6488): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentFiltersService: pid=6488 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6488): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SELinux ( 6488): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6488): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6488): TimaSignature is unavailable
,D/ActivityThread( 6488): Added TimaKeyStore provider
,I/ConfigFetchService( 1931): fetch service done; releasing wakelock
,I/ConfigFetchService( 1931): stopping self
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1931): Restart initialization of location
,W/ResourcesManager( 6472): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6472): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 24815(1182KB) AllocSpace objects, 2(36KB) LOS objects, 33% free, 23MB/35MB, paused 3.498ms total 173.529ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/MultiDex( 6472): VM with version 2.1.0 has multidex support
I/MultiDex( 6472): install
I/MultiDex( 6472): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager( 1020): Killing 5780:com.sec.android.cloudagent/u0a1 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/JNIHelp ( 6472): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/dhcpcd  ( 5642): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 5642): wlan0: no IPv6 Routers available
,W/art     ( 1931): Suspending all threads took: 10.337ms
,W/libprocessgroup( 1020): failed to open /acct/uid_10001/pid_5780/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.syncadapters.calendar, destAppInfo.processName = com.google.android.gms
,W/ActivityThread( 6472): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6472): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@311bed85: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6472): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WearableService( 6472): callingUid 10011, callindPid: 6472
,D/WVMDrmPlugIn(  284): WVMDrmPlugin::onTerminate : 3956
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1654): [180] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 5683): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 5683): Stop autocaching.
,I/VacuumService( 1692): Vacuum at: now=1451923506112 tag=VacuumService
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/CalendarProvider2( 6308): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/GoogleURLConnFactory( 1692): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/Uploader( 1692): No account for auth token provided
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6488): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/GmsUtils( 5683): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5683): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/ReminderSync( 1931): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=304:priority=5:group=main]
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/System.out( 1692): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/qtaguid ( 1931): Untagging socket 121
I/System.out( 1692): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1692): (HTTPLog)-Static: isShipBuild true
I/System.out( 1692): (HTTPLog)-Thread-214-601279533: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1692): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CheckinRequestBuilder( 1931): Checkin reason type: 12 attempt count: 1
,D/ChimeraCfgMgr( 1931): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1931): Module APK com.google.android.play.games already loaded
,E/ActivityThread( 1931): Failed to find provider info for com.google.android.wearable.settings
,W/PlaySystemBroadcastReceiver( 1931): Processed handlePeopleChanged at 170946
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1931): Loading module com.google.android.gms.games from APK com.google.android.play.games
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
D/ChimeraModuleLdr( 1931): Module APK com.google.android.play.games already loaded
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
I/System.out( 1692): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1692): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1692, getuid(): 10011
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/DataBroker( 1931): No player ID found and calling context is not the dest app
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/Finsky  ( 6488): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,I/qtaguid ( 1692): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1692, getuid(): 10011
,E/CalendarSyncAdapter( 6445): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 6445): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 6445): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 6445): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 6445): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
E/CalendarSyncAdapter( 6445): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 6445): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 6445): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 6445): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:1510)
E/CalendarSyncAdapter( 6445): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1024)
E/CalendarSyncAdapter( 6445): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:906)
E/CalendarSyncAdapter( 6445): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:430)
E/CalendarSyncAdapter( 6445): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:335)
E/CalendarSyncAdapter( 6445): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 6445): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 6445): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 6445): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 6445): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 6445): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 6445): 	... 12 more
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 22248, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1020): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 203977, reason: Periodic
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6543): MountEmulatedStorage()
,E/Zygote  ( 6543): v2
I/libpersona( 6543): KNOX_SDCARD checking this for 10011
I/libpersona( 6543): KNOX_SDCARD not a persona
,I/SELinux ( 6543): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6543): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6543 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
E/SELinux ( 6543): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Killing 5808:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/ConfigFetchService( 1931): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,D/TimaKeyStoreProvider( 6543): TimaSignature is unavailable
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/ActivityThread( 6543): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Settings( 6488): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6488): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
D/GCM     ( 1692): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigFetchService( 1931): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1931): GmsCore config value changed; rescheduling
,W/ConfigFetchService( 1931): ConfigApi client is not connected. Falling back to defaultfetch interval.
,I/splitIntent( 1020): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1020): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1020): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigFetchService( 1931): service connected
,W/ResourcesManager( 6543): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6543): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ConfigFetchService( 1931): ConfigApi connection successful.
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_5808/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1692): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,V/GmsCoreStatsServiceLauncher( 1931): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ContextImpl( 5683): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,I/MultiDex( 6543): VM with version 2.1.0 has multidex support
I/MultiDex( 6543): install
I/MultiDex( 6543): VM has multidex support, MultiDex support library is disabled.
,E/GmsUtils( 5683): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigFetchService( 1931): stopping self
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/GmsUtils( 5683): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1020): Killing 4326:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 1931): (284) automatic index on invitations(external_inviter_id)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Uploader( 1692): No account for auth token provided
,E/MDM     ( 1654): [181] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1692): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1692): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1692, getuid(): 10011
,V/JNIHelp ( 6543): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1020): Killing 5699:com.google.android.apps.books/u0a71 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,D/Finsky  ( 6488): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6488): [1] 2.run: Finished loading 1 libraries.
,D/LocationInitializer( 1931): Restart initialization of location
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6488): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ActivityThread( 6543): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6543): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@311bed85: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6543): Installed default security provider GmsCore_OpenSSL
,I/art     ( 1692): Explicit concurrent mark sweep GC freed 30434(1716KB) AllocSpace objects, 16(688KB) LOS objects, 39% free, 8MB/13MB, paused 1.180ms total 63.032ms
,D/Finsky  ( 6488): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/SSRM:n  ( 1020): SIOP:: AP = 340
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,W/libprocessgroup( 1020): failed to open /acct/uid_10039/pid_4326/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,W/libprocessgroup( 1020): failed to open /acct/uid_10071/pid_5699/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/Uploader( 1692): No account for auth token provided
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,I/System.out( 1692): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1692): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1692, getuid(): 10011
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1654): Uploading GCM registration ID for account#2#
,W/BaseAppContext( 1654): Using Auth Proxy for data requests.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1020): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1020): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1020): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
,I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1692): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1692): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/GLSUser ( 1654): [ChannelManager] Attempting to channel bind connection HttpClient.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Uploader( 1692):  no longer exists, so no auth token.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1692): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1692): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1692, getuid(): 10011
,V/GmsCoreStatsServiceLauncher( 1931): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
W/ActivityManager( 1020): userId = 0, bbcId = -10000
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1654): [182] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1654): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1931): Restart initialization of location
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Mms/MmsApp( 6266):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 6266): [start]    fillCache consume time = 1957.245468
D/Mms/ComposeMessageFragment( 6266): fillCache, easy = false
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Uploader( 1692): No account for auth token provided
,I/System.out( 1692): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1692): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1692, getuid(): 10011
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/CheckinRequestBuilder( 1931): awaiting user notification for token
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,I/CheckinRequestBuilder( 1931): Classify the device as Phone.
,I/art     ( 1654): Explicit concurrent mark sweep GC freed 17640(974KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 8MB/13MB, paused 1.194ms total 62.551ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/DataBuffer( 1654): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@255b5aaf)
,D/AbsListView( 6266): Get MotionRecognitionManager
,D/MotionRecognitionService( 1020):  ssp status : false
,D/Mms/ComposeMessageFragment( 6266): [end]    fillCache consume time = 92.8675
,I/CheckinTask( 1931): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/CheckinService( 1931): Checking schedule, now: 1451923507080 next: 1452452268064
,I/CheckinService( 1931): active receiver: disabled
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1020): Killing 5899:com.sec.android.soagent/u0a31 (adj 15): empty #31
,D/Mms/BubbleViewCache( 6266): fillCache bubble = 1
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 31689(1630KB) AllocSpace objects, 11(184KB) LOS objects, 33% free, 23MB/35MB, paused 2.831ms total 142.998ms
,I/art     ( 1020): WaitForGcToComplete blocked for 69.108ms for cause HeapTrim
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1931): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1931): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,V/Finsky  ( 6488): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/GCM     ( 1692): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/libprocessgroup( 1020): failed to open /acct/uid_10031/pid_5899/cgroup.procs: No such file or directory
,D/PersonaManager( 1181): isKioskContainerExistOnDevice,
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
,D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
E/Uploader( 1692): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1692): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1692): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1692): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1692): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1692): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1692, getuid(): 10011
,E/GCoreUlr( 1654): 
E/GCoreUlr( 1654): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1654): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1654): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1654): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1654): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1654): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1654): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1654): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1654): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1654): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1654): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1654): 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
E/GCoreUlr( 1654): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1654): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1654): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1654): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): waitForAlarm result :4
,D/Finsky  ( 6488): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 22248, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SyncManager( 1020): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 202049, reason: Periodic
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 1931): [AccountUtils] Account not ready
W/Kids    ( 1931): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1931): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1931): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1931): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1931): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1931): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1931): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1931): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1931): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1931): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1931): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1931): 	at java.lang.Thread.run(Thread.java:818)
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/Finsky  ( 6488): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/Uploader( 1692): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1692): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1692): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1692): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1692): (HTTPLog)-Static: isSBSettingEnabled false
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/qtaguid ( 1692): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1692, getuid(): 10011
I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
,D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SMD     (  290): DCD OFF
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Uploader( 1692): No account for auth token provided
,I/System.out( 1692): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1692): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1692, getuid(): 10011
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6488): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,E/Uploader( 1692): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1692): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1692): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1692): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1692): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1692): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1692, getuid(): 10011
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/Uploader( 1692): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1692): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1692): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1692): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/System.out( 1692): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1692): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1692, getuid(): 10011
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/Uploader( 1692): No account for auth token provided
,I/System.out( 1692): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1692): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1692, getuid(): 10011
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1692): No account for auth token provided
,I/System.out( 1692): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1692): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1692, getuid(): 10011
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6488): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6488): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6488): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 6488): [1] DailyHygiene.reschedule: Scheduling new run in 284 minutes (failures=4)
,D/Finsky  ( 6488): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/DeviceConnectionService( 1654): client connected with version: 7571000
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6488): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/Uploader( 1692): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1692): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1692): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1692): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1692): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/System.out( 1692): (HTTPLog)-Static: isSBSettingEnabled false
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/qtaguid ( 1692): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1692, getuid(): 10011
,I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
,D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1020): Killing 5061:com.policydm/1000 (adj 15): empty #31
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_5061/cgroup.procs: No such file or directory,
,E/SMD     (  290): DCD OFF,
,I/ConfigService( 1692): onDestroy
,W/ProcessCpuTracker( 1020): Skipping unknown process pid 6608,
,I/ActivityManager( 1020): Killing 5518:com.android.email/u0a141 (adj 15): empty #31
I/ActivityManager( 1020): Killing 5938:com.samsung.android.sconnect/u0a121 (adj 15): empty #32
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,W/libprocessgroup( 1020): failed to open /acct/uid_10141/pid_5518/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10121/pid_5938/cgroup.procs: No such file or directory
,E/SMD     (  290): DCD OFF
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5324): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5324): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5324): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5324): AutoUpdateTriggerManager:REQUEST2:requestInterval
,D/hcjo    ( 5324): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 5324): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime,
,D/PreloadUpdateManagerStateMachine( 5324): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5324): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5324): entry::REQ_UPDATE_CHECK
,I/Volley  ( 5324): RestApi Request Add : 2315
,I/System.out( 5324): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 5324): Tagging socket -1 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 5324, getuid(): 10009
,I/qtaguid ( 5324): Failed write_ctrl(t -1 8764893202948816896 -1) res=-1 errno=9
I/qtaguid ( 5324): Tagging socket -1 with tag 79a327ee00000000(2040735726) for uid -1 failed errno=-9
,I/NetworkManagementSocketTagger( 5324): tagSocketFd(-1, 2040735726, -1) failed with errno-9
,I/qtaguid ( 5324): Tagging socket 31 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 5324, getuid(): 10009
,I/qtaguid ( 5324): Untagging socket -1
,I/qtaguid ( 5324): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 5324): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger( 5324): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine( 5324): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
,D/PreloadUpdateManagerStateMachine( 5324): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 5324): entry::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 5324): exit::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 5324): entry::FINISH
,D/PreloadUpdateManagerStateMachine( 5324): exit::FINISH
,D/PreloadUpdateManagerStateMachine( 5324): entry::IDLE
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 300
,D/PackageManager( 1020): [MSG] SEND_PENDING_BROADCAST
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.PACKAGE_CHANGED
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PageBuddyNotiSvc( 3080): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RegisteredServicesCache( 1442): empty dynamic service
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/splitIntent( 1020): intent=android.intent.action.PACKAGE_CHANGED will be not split. because same process=com.google.android.googlequicksearchbox:search is in other queue. index=1
,I/splitIntent( 1020): base  index=1, name=com.google.android.googlequicksearchbox com.google.android.search.core.GmsPackageWatcher
,I/splitIntent( 1020): other index=14, name=com.google.android.googlequicksearchbox com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_CHANGED !! do not split it!!
,W/IntentResolver( 1020): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6613): MountEmulatedStorage()
I/libpersona( 6613): KNOX_SDCARD checking this for 10052
E/Zygote  ( 6613): v2
I/libpersona( 6613): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=6613 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a,
I/SELinux ( 6613): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6613): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6613): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
,D/TimaKeyStoreProvider( 6613): TimaSignature is unavailable
,D/ActivityThread( 6613): Added TimaKeyStore provider
,W/ResourcesManager( 6003): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6003): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 1458): Background sticky concurrent mark sweep GC freed 60467(3MB) AllocSpace objects, 9(144KB) LOS objects, 38% free, 5MB/8MB, paused 5.540ms total 68.457ms
,W/ResourceType( 1020): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/JNIHelp ( 6003): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,W/ActivityThread( 6003): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6003): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d61ed67: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6003): Installed default security provider GmsCore_OpenSSL
,D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1020): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService( 1020): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 1020): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 1020): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@12b45196
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/LocationManagerService( 1020): getProviders()=[passive]
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1020): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 1020): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6638): MountEmulatedStorage()
E/Zygote  ( 6638): v2
I/libpersona( 6638): KNOX_SDCARD checking this for 10014
I/libpersona( 6638): KNOX_SDCARD not a persona
,I/SELinux ( 6638): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6638 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a,
,I/SELinux ( 6638): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6638): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,V/GmsNetworkLocationProvi( 1654): DISABLE
,I/GCoreNlp( 1654): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/art     (  307): Explicit concurrent mark sweep GC freed 8688(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 19.926ms
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6638): TimaSignature is unavailable
,D/ActivityThread( 6638): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 570us total 16.626ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 16.530ms
,E/Zygote  ( 6655): MountEmulatedStorage(),
E/Zygote  ( 6655): v2
I/libpersona( 6655): KNOX_SDCARD checking this for 10029
I/libpersona( 6655): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6655 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 6655): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6655): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms,
E/SELinux ( 6655): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Killing 5735:com.google.android.youtube/u0a161 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6655): TimaSignature is unavailable
,D/ActivityThread( 6655): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/LocationProviderProxy( 1020): applying state to connected service
,D/LocationProviderProxy( 1020): applying state to connected service
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 41671(2MB) AllocSpace objects, 10(185KB) LOS objects, 33% free, 23MB/35MB, paused 2.584ms total 151.227ms
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup( 1020): failed to open /acct/uid_10161/pid_5735/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/FeatureConfig( 6655): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6655): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.,
W/ResourcesManager( 6655): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6655): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 6674): MountEmulatedStorage(),
E/Zygote  ( 6674): v2
I/libpersona( 6674): KNOX_SDCARD checking this for 10039
I/libpersona( 6674): KNOX_SDCARD not a persona
,I/SELinux ( 6674): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6674 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux ( 6674): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6674): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/Babel   ( 6003): UserRecoverableAuthException.
,E/Babel   ( 6003): eei: BadAuthentication
E/Babel   ( 6003): 	at eeg.a(Unknown Source)
E/Babel   ( 6003): 	at eeg.a(Unknown Source)
E/Babel   ( 6003): 	at eeg.a(Unknown Source)
E/Babel   ( 6003): 	at g.a(Unknown Source)
E/Babel   ( 6003): 	at cae.a(SourceFile:3089)
E/Babel   ( 6003): 	at cae.a(SourceFile:1131)
E/Babel   ( 6003): 	at cws.a(SourceFile:4333)
E/Babel   ( 6003): 	at cws.a(SourceFile:1419)
E/Babel   ( 6003): 	at crl.a(SourceFile:492)
E/Babel   ( 6003): 	at crl.a(SourceFile:1468)
E/Babel   ( 6003): 	at cqu.a(SourceFile:4416)
E/Babel   ( 6003): 	at cas.b(SourceFile:106)
E/Babel   ( 6003): 	at cap.d(SourceFile:335)
E/Babel   ( 6003): 	at caq.run(SourceFile:81)
,E/Babel   ( 6003): Error getting auth token
,E/Babel   ( 6003): dvm
E/Babel   ( 6003): 	at g.a(Unknown Source)
E/Babel   ( 6003): 	at cae.a(SourceFile:3089)
E/Babel   ( 6003): 	at cae.a(SourceFile:1131)
E/Babel   ( 6003): 	at cws.a(SourceFile:4333)
E/Babel   ( 6003): 	at cws.a(SourceFile:1419)
E/Babel   ( 6003): 	at crl.a(SourceFile:492)
E/Babel   ( 6003): 	at crl.a(SourceFile:1468)
E/Babel   ( 6003): 	at cqu.a(SourceFile:4416)
E/Babel   ( 6003): 	at cas.b(SourceFile:106)
E/Babel   ( 6003): 	at cap.d(SourceFile:335)
E/Babel   ( 6003): 	at caq.run(SourceFile:81)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/Babel   ( 6003): Account registration failed 1-Redacted-21
,W/ResourcesManager( 6655): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6655): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/Babel   ( 6003): cyp: null -- null
E/Babel   ( 6003): 	at cae.a(SourceFile:3121)
E/Babel   ( 6003): 	at cae.a(SourceFile:1131)
E/Babel   ( 6003): 	at cws.a(SourceFile:4333)
E/Babel   ( 6003): 	at cws.a(SourceFile:1419)
E/Babel   ( 6003): 	at crl.a(SourceFile:492)
E/Babel   ( 6003): 	at crl.a(SourceFile:1468)
E/Babel   ( 6003): 	at cqu.a(SourceFile:4416)
E/Babel   ( 6003): 	at cas.b(SourceFile:106)
E/Babel   ( 6003): 	at cap.d(SourceFile:335)
E/Babel   ( 6003): 	at caq.run(SourceFile:81)
,D/TimaKeyStoreProvider( 6674): TimaSignature is unavailable
,D/ActivityThread( 6674): Added TimaKeyStore provider
,I/System.out( 6003): (HTTPLog)-Static: isSBSettingEnabled false
,I/art     ( 6003): Note: end time exceeds epoch: 
,W/ResourcesManager( 6655): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6674): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6674): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6674): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6674): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6674): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6674): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6674): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,W/ResourcesManager( 6655): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 6655): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6655): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6655): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ResourcesManager( 6655): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 6655): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6655): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 1692): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6655): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ResourcesManager( 6655): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Babel   ( 6003): Unexpected exception while authenticating.
,E/Babel   ( 6003): eej: User intervention required. Notification has been pushed.
E/Babel   ( 6003): 	at eeg.b(Unknown Source)
E/Babel   ( 6003): 	at eeg.b(Unknown Source)
E/Babel   ( 6003): 	at g.a(Unknown Source)
E/Babel   ( 6003): 	at cae.b(SourceFile:1146)
E/Babel   ( 6003): 	at dcg.run(SourceFile:5617)
E/Babel   ( 6003): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6003): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6003): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
,D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/GalaxyFinderApplication( 6655): system/finder_cp/cpdata.xml file not found
,D/NearbySource( 6674): Nearby Source Create!
,D/NearbyContext( 6674): Nearby Context Create!
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6674): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 6674): Samsung link source created
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/ContactProvider( 6674): getAllContactInfoList Start
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/PackagesMonitor( 6674): PackagesMonitor onReceive :com.google.android.gms
,D/ContactProvider( 6674): getAllContactInfoList End
,I/syncContacts( 6674): thread: 1118, sync time = 33
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6697 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 6197:com.android.chrome/u0a77 (adj 15): empty #31
,E/Zygote  ( 6697): MountEmulatedStorage(),
E/Zygote  ( 6697): v2
I/libpersona( 6697): KNOX_SDCARD checking this for 10065
I/libpersona( 6697): KNOX_SDCARD not a persona
I/SELinux ( 6697): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6697): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6697): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6697): TimaSignature is unavailable
,D/ActivityThread( 6697): Added TimaKeyStore provider
,D/FileShare-Server( 6697): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6712): MountEmulatedStorage(),
,E/Zygote  ( 6712): v2,
I/libpersona( 6712): KNOX_SDCARD checking this for 1000
I/libpersona( 6712): KNOX_SDCARD not a persona
,I/SELinux ( 6712): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6712 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 6107:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
,I/SELinux ( 6712): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6712): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6712): TimaSignature is unavailable
,D/ActivityThread( 6712): Added TimaKeyStore provider
,W/ResourcesManager( 6712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup( 1020): failed to open /acct/uid_10077/pid_6197/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10110/pid_6107/cgroup.procs: No such file or directory
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6727): MountEmulatedStorage(),
E/Zygote  ( 6727): v2
I/libpersona( 6727): KNOX_SDCARD checking this for 1000,
I/libpersona( 6727): KNOX_SDCARD not a persona
,I/SELinux ( 6727): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1020): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=6727 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 6066:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,I/SELinux ( 6727): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6727): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6727): TimaSignature is unavailable
D/ActivityThread( 6727): Added TimaKeyStore provider
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/ShortcutReceiver( 6727):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,I/ActivityManager( 1020): Killing 5284:com.google.android.apps.plus/u0a117 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PackageBroadcastService( 1931): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PackageBroadcastService( 1931): Null package name or gms related package.  Ignoreing.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Icing   ( 1931): updateResources: need to parse f{com.google.android.gms}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1020): failed to open /acct/uid_10087/pid_6066/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10117/pid_5284/cgroup.procs: No such file or directory
,E/Zygote  ( 6744): MountEmulatedStorage(),
I/libpersona( 6744): KNOX_SDCARD checking this for 10117
E/Zygote  ( 6744): v2
,I/libpersona( 6744): KNOX_SDCARD not a persona
I/SELinux ( 6744): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PhotosAppTransitionMonitor: pid=6744 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6744): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6744): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6744): TimaSignature is unavailable
,D/ActivityThread( 6744): Added TimaKeyStore provider
,W/ResourcesManager( 6744): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/UpdateIcingCorporaServi( 6613): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 6613): UpdateCorporaTask done [took 129 ms] updated apps [took 129 ms] 
,I/ActivityManager( 1020): Killing 5852:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,W/libprocessgroup( 1020): failed to open /acct/uid_10008/pid_5852/cgroup.procs: No such file or directory
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ActivityManager( 1020): Killing 6234:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,W/libprocessgroup( 1020): failed to open /acct/uid_10058/pid_6234/cgroup.procs: No such file or directory
,I/ActivityManager( 1020): Killing 5115:com.osp.app.signin/u0a36 (adj 15): empty #31
,W/libprocessgroup( 1020): failed to open /acct/uid_10036/pid_5115/cgroup.procs: No such file or directory
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1020): waitForAlarm result :4
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 140s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1020): !@Sync 6
,E/SMD     (  290): DCD OFF
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms,
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.youtube
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6777): MountEmulatedStorage()
E/Zygote  ( 6777): v2
I/libpersona( 6777): KNOX_SDCARD checking this for 10161
,I/libpersona( 6777): KNOX_SDCARD not a persona
,I/SELinux ( 6777): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6777 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6777): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6777): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6777): TimaSignature is unavailable
,D/ActivityThread( 6777): Added TimaKeyStore provider
,W/ResourcesManager( 6777): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6777): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6777): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6777): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6777): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14d55e7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6777): Installed default security provider GmsCore_OpenSSL
,I/dex2oat ( 6802): ----------------------------------------------------
I/dex2oat ( 6802): <SS>: S T A R T I N G . . .
I/dex2oat ( 6802): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 6802): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads668578441.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads668578441.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/YouTube MDX( 6777): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/dex2oat ( 6802): dex2oat took 45.862ms (threads: 4)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6777): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6488): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6488): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6488): [1] 5.onFinished: Giving up after 6 failures.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6777): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6777): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6777): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 6777): Found 10011
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6777): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/ActivityManager( 1020): Killing 6075:com.sec.spp.push/u0a32 (adj 15): empty #31
,D/AndroidHttpClient( 6777): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
,D/AndroidHttpClient( 6777): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 6777): Thread-1198(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6777): Thread-1198(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6777): Thread-1198(ApacheHTTPLog):isShipBuild true
I/System.out( 6777): Thread-1198(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 6777): Thread-1198(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10161
,W/libprocessgroup( 1020): failed to open /acct/uid_10032/pid_6075/cgroup.procs: No such file or directory
,I/System.out( 6777): Thread-1198 calls detatch()
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6866): MountEmulatedStorage()
,E/Zygote  ( 6866): v2
I/libpersona( 6866): KNOX_SDCARD checking this for 10071
I/libpersona( 6866): KNOX_SDCARD not a persona
I/SELinux ( 6866): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6866): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1020): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6866 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6866): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6875): MountEmulatedStorage(),
E/Zygote  ( 6875): v2
I/libpersona( 6875): KNOX_SDCARD checking this for 10087
I/libpersona( 6875): KNOX_SDCARD not a persona
,I/SELinux ( 6875): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1020): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=6875 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/SELinux ( 6875): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6875): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6866): TimaSignature is unavailable
D/ActivityThread( 6866): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 6875): TimaSignature is unavailable
,D/ActivityThread( 6875): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 6866): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BooksApp( 6866): Created application version: 3.6.9 (30609)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  290): DCD OFF
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BooksSync( 6866): Starting books sync for 61035162, extras: ade
,I/GAv4    ( 6875): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6875):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6875):   adb logcat -s GAv4
,W/GAv4    ( 6875): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6875): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6875): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 6875): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.33
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 33317(1811KB) AllocSpace objects, 13(212KB) LOS objects, 33% free, 23MB/35MB, paused 2.638ms total 150.819ms
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/,
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6875): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 6875): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6875): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6875): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6875): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6875): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/SQLiteLog( 6866): (284) automatic index on view_volumes(volume_id)
,I/BooksConfig( 6866): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityThread( 6875): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6875): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16502078: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6875): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 1931): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1931): Module APK com.google.android.play.games already loaded
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AccountUtils( 1931): 0 accounts found with uca feature
,I/GamesSyncAdapter( 1931): Starting sync for 3a3529a
,I/GamesSyncAdapter( 1931): Sync duration for 3a3529a: 4
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1931): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1931): Module APK com.google.android.play.games already loaded
,I/art     ( 1692): Explicit concurrent mark sweep GC freed 33460(1880KB) AllocSpace objects, 47(2MB) LOS objects, 39% free, 8MB/13MB, paused 1.130ms total 45.842ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6866): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6866): Soft error
E/BooksSync( 6866): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6866): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6866): Sync error
E/BooksSync( 6866): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6866): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6866): Finished books sync
,I/ActivityManager( 1020): Killing 6287:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,I/ActivityManager( 1020): Killing 6266:com.android.mms/u0a41 (adj 15): empty #32
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 192358, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
,D/CountryDetector( 1020): No listener is left
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1931): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1931): Module APK com.google.android.play.games already loaded
,W/libprocessgroup( 1020): failed to open /acct/uid_10081/pid_6287/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10041/pid_6266/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,V/AlarmManager( 1020): waitForAlarm result :8
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 6866): Thread[GAThread,5,main]: No campaign data found.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/Watchdog( 1020): !@Sync 7
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,D/Finsky  ( 6488): [1085] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6488): [1085] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/PowerManagerService( 1020): [PWL] Off : 180s ago,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1020): !@Sync 8
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 225s ago
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/BooksSync( 6866): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6866): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
,D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6866): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
E/BooksSync( 6866): Soft error
E/BooksSync( 6866): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6866): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6866): Sync error
E/BooksSync( 6866): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6866): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6866): Finished books sync
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 281557, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SQLiteLog( 1692): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1020): !@Sync 9
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TimaServiceHandler.handleMessage what =1,
D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 1020): initializing...,
I/TLC_TIMA_PKM_initialize( 1020): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1020): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1020): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1020): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1020): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1020): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1020): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1020): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1020): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1020): Loaded image: APP id = 10
,I/TZ: qc_tlc_communication( 1020): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1020): Trustlet response is completed
,E/SMD     (  290): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/Watchdog( 1020): !@Sync 10,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 275s ago
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1020): !@Sync 11,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1020): !@Sync 12
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 330s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6866): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6866): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6866): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6866): Soft error
E/BooksSync( 6866): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6866): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6866): Sync error
E/BooksSync( 6866): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6866): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6866): Finished books sync
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 403331, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,V/AlarmManager( 1020): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 13
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 14
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5451): Disconnected process message: 10
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 390s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1020): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 15
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 45566(3MB) AllocSpace objects, 107(1726KB) LOS objects, 33% free, 23MB/35MB, paused 2.465ms total 165.372ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1692): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1692): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1692): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1692): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1692): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1181): isKioskContainerExistOnDevice,
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
E/PlayEventLogger( 6488): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6488): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6488): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6488): ,	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6488): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6488): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6488): 	at android.os.Binder.execTransact(Binder.java:461)
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only,
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/System  ( 6488): Ignoring header User-Agent because its value was null.
,I/System.out( 6488): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6488): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6488): (HTTPLog)-Static: isShipBuild true
I/System.out( 6488): (HTTPLog)-Thread-1108-887526188: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6488): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10026
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
,I/System.out( 6488): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/bootchecker(  312): bootchecker wake up!!,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1020): !@Sync 16
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/AndroidHttpClient( 6777): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
,D/AndroidHttpClient( 6777): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
I/System.out( 6777): Thread-1198(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6777): Thread-1198(ApacheHTTPLog):isShipBuild true
I/System.out( 6777): Thread-1198(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6777): Thread-1198(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10161
,I/System.out( 6777): Thread-1198 calls detatch()
,D/AndroidHttpClient( 6777): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
,D/AndroidHttpClient( 6777): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 6777): Thread-1198(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6777): Thread-1198(ApacheHTTPLog):isShipBuild true
,I/System.out( 6777): Thread-1198(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6777): Thread-1198(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/System.out( 6777): Thread-1198 calls detatch()
,D/AndroidHttpClient( 6777): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
,D/AndroidHttpClient( 6777): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
I/System.out( 6777): Thread-1198(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6777): Thread-1198(ApacheHTTPLog):isShipBuild true
I/System.out( 6777): Thread-1198(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6777): Thread-1198(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 6777): Thread-1198 calls detatch()
,D/AndroidHttpClient( 6777): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
,D/AndroidHttpClient( 6777): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 6777): Thread-1198(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6777): Thread-1198(ApacheHTTPLog):isShipBuild true
I/System.out( 6777): Thread-1198(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6777): Thread-1198(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 6777): Thread-1198 calls detatch()
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1020): [PWL] Off : 455s ago
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 17
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1020): !@Sync 18,
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 525s ago,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,I/Atfwd_Daemon(  315): Stop the daemon....,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1020): !@Sync 19
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 20
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate,
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/BooksSync( 6866): Starting books sync for 61035162, extras: ade
D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 6866): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6866): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6866): Soft error
E/BooksSync( 6866): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6866): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6866): Sync error
E/BooksSync( 6866): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6866): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6866): Finished books sync
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 646596, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,E/Watchdog( 1020): !@Sync 21
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,I/PowerManagerService( 1020): [PWL] Off : 600s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,E/Watchdog( 1020): !@Sync 22
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 23
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 681s ago,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 24
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 25,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 26
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 766s ago,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 27
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1020): Plugged
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 28
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 29
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 856s ago,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1020): TimaServiceHandler.handleMessage what =1,
,E/SMD     (  290): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1020): !@Sync 30
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 31
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1020): SIOP:: AP = 250,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 32
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 951s ago,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 33
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 34
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1692): Message class com.google.f.a.a.i
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GCM     ( 1931): Message from null null
E/GCM     ( 1931): Dropping message from null
,V/AlarmManager( 1020): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 35,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1020): !@Sync 36,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 1051s ago,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1020): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,D/SSRM:n  ( 1020): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1020): !@Sync 37
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/BooksSync( 6866): Starting books sync for 61035162, extras: ade
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,I/BooksConfig( 6866): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
,D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1692): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1692): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1692): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1692): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6866): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6866): Soft error
E/BooksSync( 6866): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6866): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6866): Sync error
E/BooksSync( 6866): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6866): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6866): Finished books sync
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1132907, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
,W/ResourcesManager( 2372): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1020): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1020): !@Sync 38,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,V/AlarmManager( 1020): waitForAlarm result :4
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1020): waitForAlarm result :8
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1020): !@Sync 39
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 1156s ago
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1020): User[0] Flushing usage stats to disk,
,I/ApplicationUsage( 1020): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1020): Updating Usage Statistics in DB @ 1451924550987
,I/ApplicationPolicy( 1020): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1020): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1020): ::isTableExists: Table exists 
,I/ApplicationUsage( 1020): Done Updating Usage Statistics in DB @ 1451924551385
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1020): !@Sync 40
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1020): !@Sync 41
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 250,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1020): !@Sync 42
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1020): stay LED for fully charged
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1020): Plugged
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,D/SSRM:n  ( 1020): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 43
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 1266s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 44
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 45
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 46
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 47
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 1381s ago
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 48,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 49
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250,
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1020): !@Sync 50
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5451): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5451): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1020): !@Sync 51
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 1501s ago,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1020): !@Sync 52
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1020): !@Sync 53
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1020): !@Sync 54
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 55
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1020): [PWL] Off : 1626s ago
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1020): !@Sync 56
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1020): !@Sync 57
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1020): !@Sync 58
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1020): !@Sync 59
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 1756s ago,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1020): !@Sync 60
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1020): !@Sync 61
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1020): !@Sync 62
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1020): !@Sync 63
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1020): !@Sync 64
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 1891s ago,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 250
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7665): 
D/AndroidRuntime( 7665): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7665): CheckJNI is OFF
D/AndroidRuntime( 7665): readGMSProperty: start
D/AndroidRuntime( 7665): readGMSProperty: already setted!!
D/AndroidRuntime( 7665): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7665): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7665): readGMSProperty: end
D/AndroidRuntime( 7665): addProductProperty: start
E/AffinityControl( 7665): AffinityControl: registerfunction enter
D/AndroidRuntime( 7665): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1020): START PACKAGE DELETE: observer{82834139}
D/PackageManager( 1020): pkg{<packageName>}
D/PackageManager( 1020): user{0}
D/PackageManager( 1020): caller{2000}
D/PackageManager( 1020): flags{3}
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1020): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1020): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1020): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1020): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1020): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1020): !@killApplicatoin: 10338, uninstall pkg
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1020): Killing 5400:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1020): Skipping PackageSetting{28e0f407 com.example.hello/10346} due to missing metadata
I/ActivityManager( 1020): Killing 1603:com.sec.android.daemonapp/u0a157 (adj 15): SPC_empty #31
I/ActivityManager( 1020): Killing 1566:com.sec.android.widgetapp.ap.hero.accuweather/u0a62 (adj 15): SPC_empty #32
I/ActivityManager( 1020): Killing 1296:com.android.settings/1000 (adj 15): SPC_empty #33
I/ActivityManager( 1020): Killing 3406:com.samsung.hs20settings/1000 (adj 15): SPC_empty #34
I/ActivityManager( 1020): Killing 2538:com.sec.phone/1001 (adj 15): SPC_empty #35
I/ActivityManager( 1020): Killing 3496:com.sec.bcservice/1000 (adj 15): SPC_empty #36
I/ActivityManager( 1020): Killing 3080:com.sec.android.pagebuddynotisvc/u0a113 (adj 15): SPC_empty #37
I/ActivityManager( 1020): Killing 2668:com.samsung.android.providers.context/u0a2 (adj 15): SPC_empty #38
I/ActivityManager( 1020):   Force finishing activity ActivityRecord{3e0d4c6c u0 com.test.thalitest/.MainActivity t20}
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
I/ActivityManager( 1020):   Force finishing activity ActivityRecord{3e0d4c6c u0 com.test.thalitest/.MainActivity t20 f}
I/WindowState( 1020): WIN DEATH: Window{16aef21e u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  259): id=12 Removed NainActivit (6/8)
I/SurfaceFlinger(  259): id=12 Removed NainActivit (-2/8)
W/ActivityManager( 1020): Duplicate finish request for ActivityRecord{3e0d4c6c u0 com.test.thalitest/.MainActivity t20 f}
D/InputDispatcher( 1020): Focus left window: 5400
I/SurfaceFlinger(  259): id=12 Removed NainActivit (-2/8)
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager( 1020): CustomStartingWindow se packge removed so remove capture also
I/art     ( 3673): Explicit concurrent mark sweep GC freed 3135(187KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 748us total 27.635ms
I/ProcessStatsService( 1020): Prepared write state in 20ms
D/GpsStatusListenerHelper( 1020): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@268b5178
D/InputDispatcher( 1020): Focused application released
W/ActivityManager( 1020): Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 1000ms
W/ActivityManager( 1020): Scheduling restart of crashed service com.android.settings/.wifi.WifiCredService in 10996ms
W/ActivityManager( 1020): Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 20993ms
W/ActivityManager( 1020): Scheduling restart of crashed service com.samsung.android.providers.context/.ContextService in 3866126ms
W/ActivityManager( 1020): Scheduling restart of crashed service com.samsung.hs20settings/.WifiHs20UtilityService in 30987ms
I/ProcessStatsService( 1020): Prepared write state in 8ms
E/lowmemorykiller(  256): Error opening /proc/2538/oom_score_adj; errno=2
W/ActivityManager( 1020): ProcessRecord{16f47051 2538:com.sec.phone/1001} is already killed
W/ActivityManager( 1020): Exception when unbinding service com.sec.phone/.SecPhoneService
W/ActivityManager( 1020): android.os.DeadObjectException
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
W/ActivityManager( 1020): ProcessRecord{16f47051 2538:com.sec.phone/1001} is already killed
W/ActivityManager( 1020): Scheduling restart of crashed service com.sec.bcservice/.BroadcastService in 40965ms
W/ActivityManager( 1020): Scheduling restart of crashed service com.sec.android.widgetapp.ap.hero.accuweather/.WeatherClockScreenService in 50963ms
I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1654): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 1781): mOCRHelper is null
W/BroadcastQueue( 1020): Skipping deliver [background] BroadcastRecord{3ef0e1b7 u0 android.intent.action.PACKAGE_REMOVED} to ReceiverList{275bc8f 2668 com.samsung.android.providers.context/10002/u0 remote:3e594fee}: filter unregistered
W/ResourcesManager( 1458): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/KLMS-2.5.123: ( 3448): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 04 17:34:58 GMT+01:00 2016
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3448): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1020): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1020): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1020): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
D/elm:15121( 6364): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 6364): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 6364): ElmAgentService : onCreate()
I/KLMS-2.5.123: ( 3448): KLMSIntentService(): onCreate()
D/elm:15121( 6364): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
I/KLMS-2.5.123: ( 3448): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/elm:15121( 6364): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6364): MDMBridge.getInstance()
D/elm:15121( 6364): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 6364): MDMBridge.getAllLicenseInfoFromSDK()
I/KLMS-2.5.123: ( 3448): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/elm:15121( 6364): ElmAgentService : onDestroy().
I/KLMS-2.5.123: ( 3448): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.123: ( 3448): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3448): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.123: ( 3448): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
I/art     ( 1020): Explicit concurrent mark sweep GC freed 42861(5MB) AllocSpace objects, 276(4MB) LOS objects, 33% free, 23MB/35MB, paused 2.831ms total 260.559ms
I/art     ( 1020): WaitForGcToComplete blocked for 231.214ms for cause Explicit
D/RegisteredServicesCache( 1442): empty dynamic service
D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
D/RCPManagerService( 1020): PackageReceiver onReceive()
I/HarmonyEASService( 1020): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1020): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/ProcessStatsService( 1020): Pruning old procstats: /data/system/procstats/state-2016-01-03-15-26-19.bin
W/libprocessgroup( 1020): failed to open /acct/uid_10157/pid_1603/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_1296/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10113/pid_3080/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10002/pid_2668/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3406/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3496/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10062/pid_1566/cgroup.procs: No such file or directory
I/KLMS-2.5.123: ( 3448): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.123: ( 3448): KLMSIntentService(): onDestroy()
D/EnterpriseDeviceManagerService( 1020): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1020): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1020): no available spell checker services found
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/art     ( 1020): Explicit concurrent mark sweep GC freed 14921(716KB) AllocSpace objects, 1(65KB) LOS objects, 33% free, 23MB/35MB, paused 3.338ms total 181.778ms
W/ResourceType( 1020): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
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
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10338
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
D/SSRM:aZ ( 1020): MSG_TYPE_APP_REMOVED::
D/TaskPersister( 1020): removeObsoleteFile: deleting file=20_task.xml
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.test.thalitest
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
W/ResourcesManager( 1020): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 7680): MountEmulatedStorage()
I/ActivityManager( 1020): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7680 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 7680): v2
I/libpersona( 7680): KNOX_SDCARD checking this for 1000
I/libpersona( 7680): KNOX_SDCARD not a persona
I/SELinux ( 7680): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7680): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7680): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PackageManager( 1020): delete codoeFile: 
D/AASAuninstall( 1020): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1020): UID=10338 Target=com.test.thalitest
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 1020): result of delete: 1{82834139}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/TimaKeyStoreProvider( 7680): TimaSignature is unavailable
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ActivityThread( 7680): Added TimaKeyStore provider
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1020): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1020): onPackageRemoved : com.test.thalitest
W/libprocessgroup( 1020): failed to open /acct/uid_1001/pid_2538/cgroup.procs: No such file or directory
D/AndroidRuntime( 7665): Shutting down VM
I/PCWCLIENTTRACE_LOG( 7680): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7680): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7680): new DMDBOpenHelper instance
I/PCWCLIENTTRACE_PushUtil( 7680): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7680): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7680): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7680): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7695): MountEmulatedStorage()
E/Zygote  ( 7695): v2
I/libpersona( 7695): KNOX_SDCARD checking this for 10036
I/libpersona( 7695): KNOX_SDCARD not a persona
W/ResourcesManager( 6655): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
I/SELinux ( 7695): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/ResourcesManager( 6655): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/SELinux ( 7695): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7695): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 6655): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/ActivityManager( 1020): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=7695 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 5565:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
W/ResourcesManager( 6655): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 7695): TimaSignature is unavailable
D/ActivityThread( 7695): Added TimaKeyStore provider
I/art     (  307): Explicit concurrent mark sweep GC freed 8709(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 704us total 19.631ms
W/ResourcesManager( 6655): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 568us total 17.177ms
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 19.019ms
W/ResourcesManager( 6655): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_5565/cgroup.procs: No such file or directory
W/ResourcesManager( 6655): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
I/SA      ( 7695): [SSP] onCreated
I/SA      ( 7695): [TPM] There is no property file
I/SA      ( 7695): [SCU] isHaveSA() - false
I/SA      ( 7695): [TPM] getModelProperty : null
I/SA      ( 7695): [TPM] getCSCProperty : null
W/ResourcesManager( 6655): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/SA      ( 7695): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 7695): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 7695): [DM] TFT FEATURE: false
I/SA      ( 7695): [DM] init START
I/SA      ( 7695): [DM] This device is not a Vodafone
W/ResourcesManager( 6655): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6655): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourceType( 7695): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
W/ResourceType( 7695): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 7695): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 7695): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 7695): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 7695): [SCU] isHaveSA() - false
I/SA      ( 7695): support phone number id : false
I/SA      ( 7695): [DM] Supports Ref Jpn : true
I/SA      ( 7695): [DM] init END
I/SA      ( 7695): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 7695): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager( 1020): Killing 6322:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
I/PackagesMonitor( 6674): PackagesMonitor onReceive :com.test.thalitest
W/art     ( 7665): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7714): MountEmulatedStorage()
E/Zygote  ( 7714): v2
I/libpersona( 7714): KNOX_SDCARD checking this for 10041
I/libpersona( 7714): KNOX_SDCARD not a persona
I/SELinux ( 7714): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=7714 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/SELinux ( 7714): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7714): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7714): TimaSignature is unavailable
D/ActivityThread( 7714): Added TimaKeyStore provider
W/ResourcesManager( 7714): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7714): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7714): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7714): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7714): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/Mms/MmsApp( 7714): [start]    onCreate() consume time = 0.0

```
