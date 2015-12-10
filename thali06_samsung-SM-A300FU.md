#### Test 506502784dae475_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
I/ServiceManager(  331): Waiting for service AtCmdFwd...
E/SMD     (  292): DCD OFF
,D/AndroidRuntime( 5460): 
D/AndroidRuntime( 5460): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5460): CheckJNI is OFF
D/AndroidRuntime( 5460): readGMSProperty: start
D/AndroidRuntime( 5460): readGMSProperty: already setted!!
D/AndroidRuntime( 5460): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5460): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5460): readGMSProperty: end
D/AndroidRuntime( 5460): addProductProperty: start
E/AffinityControl( 5460): AffinityControl: registerfunction enter
D/AndroidRuntime( 5460): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
W/ActivityManager( 1019): mDVFSHelper.acquire()
D/FocusedStackFrame( 1019): Set to : 0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1019): *FMB* installDecor flags : 25362712
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5473 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/libpersona( 5473): KNOX_SDCARD checking this for 10338
D/InputDispatcher( 1019): Focused application set to: xxxx
I/libpersona( 5473): KNOX_SDCARD not a persona
E/Zygote  ( 5473): MountEmulatedStorage()
E/Zygote  ( 5473): v2
D/InputDispatcher( 1019): Focus left window: 1478
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
D/AndroidRuntime( 5460): Shutting down VM
I/SELinux ( 5473): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 5473): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5473): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5473): TimaSignature is unavailable
D/ActivityThread( 5473): Added TimaKeyStore provider
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1019): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1478): updateVisibility : ActivityRecord{4f3882f token=android.os.BinderProxy@3a1fdafa {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1478): onTrimMemory. Level: 20
I/WebViewFactory( 5473): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5473): Time to load native libraries: 1 ms (timestamps 1102-1103)
I/LibraryLoader( 5473): Expected native library version number "",actual native library version number ""
W/art     ( 5460): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 5473): Binding Chromium to main looper Looper (main, tid 1) {34aaf42d}
,I/LibraryLoader( 5473): Expected native library version number "",actual native library version number ""
,I/chromium( 5473): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5473): Initializing chromium process, singleProcess=true
,W/art     ( 5473): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5473): ApplicationContext is null in ApplicationStatus
,W/chromium( 5473): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5473): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5473): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5473): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5473): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5473): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5473): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5473): Local Branch: 
I/Adreno-EGL( 5473): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5473): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5473):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/BluetoothAdapter( 5473): 241200558: getState() :  mService = null. Returning STATE_OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/art     ( 5473): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5473): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5473): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5473): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5473): CordovaWebView is running on device made by: samsung
,W/art     ( 5473): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5473): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1019): Activity pause timeout for ActivityRecord{394bf6c2 u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 5473): Render dirty regions requested: true
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,W/chromium( 5473): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 5473): updateVisibility : ActivityRecord{1bdd423f token=android.os.BinderProxy@8e16b99 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 5473): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5473): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1019): Focus entered window: 5473
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 5473): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 5473): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5473): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5473): Enabling debug mode 0
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
,I/ActivityManager( 1019): Displayed Component not be shown by security: +679ms (total +54s761ms)
,W/ActivityManager( 1019): mDVFSHelper.release()
,I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{394bf6c2 u0 com.test.thalitest/.MainActivity t20} time:161628
,I/SurfaceFlinger(  258): id=11 Removed uhalitest (7/9)
,I/SurfaceFlinger(  258): id=11 Removed uhalitest (-2/9)
,W/IInputConnectionWrapper( 5473): showStatusIcon on inactive InputConnection
I/SamsungIME( 1763): getCurrentCandidateView
,I/Timeline( 5473): Timeline: Activity_idle id: android.os.BinderProxy@8e16b99 time:161642
,D/SamsungIME( 1763): Dismiss ExpandCandiate
,I/SamsungIME( 1763): getDebugLevel  : 0x4f4c
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/SamsungIME( 1763): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1763): KeybaordView init() : load resources
,I/SamsungIME( 1763): getCurrentKeyboard
,I/SamsungIME( 1763): getTextKeyboard
,W/BindingManager( 5473): Cannot call determinedVisibility() - never saw a connection for the pid: 5473
,D/SamsungIME( 1763): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 5473): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5473): JniHelper::setJavaVM(0xb7054448), pthread_self() = -1218791288
,D/JX-Cordova( 5473): jxcore cordova android initializing
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,V/AlarmManager( 1019): waitForAlarm result :4
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 4
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1657): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1657): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1657): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1657): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/SMD     (  292): DCD OFF
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4742): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4742): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4742): [1] 5.onFinished: Scheduling replication attempt 5.
,W/jxcore-log( 5473): Initializing JXcore engine
W/jxcore-log( 5473): JXcore engine is ready
,W/jxcore-log( 5473): Starting JXcore engine
,E/audit   ( 1804): type=1400 msg=audit(1449751057.741:203): avc:  denied  { ioctl } for  pid=5473 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1804):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1804): type=1300 msg=audit(1449751057.741:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=2 a3=bea8ad58 items=0 ppid=317 ppcomm=main pid=5473 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1804): type=1320 msg=audit(1449751057.741:203): 
,W/jxcore-log( 5473): Platform android
W/jxcore-log( 5473): 
W/jxcore-log( 5473): Process ARCH arm
W/jxcore-log( 5473): 
,I/jxcore-log( 5473): JXcore Cordova bridge is ready!,
I/jxcore-log( 5473): 
W/jxcore-log( 5473): JXcore engine is started
,I/Choreographer( 5473): Skipped 131 frames!  The application may be doing too much work on its main thread.
,I/chromium( 5473): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 5473): Toggling radios to true
I/jxcore-log( 5473): 
,D/BluetoothAdapter( 5473): enable()
,W/ActivityManager( 1019): Permission Denial: getCurrentUser() from pid=5473, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 1019): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 1019): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5473, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 1019): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/BluetoothManagerService( 1019): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
W/BluetoothManagerService( 1019): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
W/BluetoothManagerService( 1019): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/BluetoothManagerService( 1019): 	at android.os.Binder.execTransact(Binder.java:461)
,E/DevicePolicyManagerService( 1019): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1019): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider( 1019): name = bluetooth_on,
,E/DevicePolicyManagerService( 1019): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1019): getAllowBluetoothMode - value retunrs : 2
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5523 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,E/Zygote  ( 5523): MountEmulatedStorage()
I/libpersona( 5523): KNOX_SDCARD checking this for 1002
E/Zygote  ( 5523): v2,
I/libpersona( 5523): KNOX_SDCARD not a persona
I/SELinux ( 5523): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5523): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 5523): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecContentProvider( 1019): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1019): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1019): mCursor = null
,D/WifiService( 1019): setWifiEnabled: true pid=5473, uid=10338
,W/ActivityManager( 1019): Permission Denial: getCurrentUser() from pid=5473, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1019): Failed getting userId using ActivityManagerNative
W/WifiService( 1019): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5473, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1019): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1019): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1019): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1019): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1019): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1019): name = wifi_on
D/TimaKeyStoreProvider( 5523): TimaSignature is unavailable
D/ActivityThread( 5523): Added TimaKeyStore provider
I/WifiService( 1019): disconnect: pid=5473, uid=10338
I/jxcore-log( 5473): Radios toggled
I/jxcore-log( 5473): 
E/WifiHW  ( 1019): ##################### set firmware type 0 #####################
,W/ResourcesManager( 5523): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 5523): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni( 5523): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 5523): Adding GattService
,D/BtSettings.ProfileConfig( 5523): Adding HeadsetService
,D/BtSettings.ProfileConfig( 5523): Adding A2dpService
,D/BtSettings.ProfileConfig( 5523): Adding HidService
D/BtSettings.ProfileConfig( 5523): Adding HealthService
,D/BtSettings.ProfileConfig( 5523): Adding PanService
,D/BtSettings.ProfileConfig( 5523): Adding BluetoothMapService
D/BtSettings.ProfileConfig( 5523): Adding SapService
,D/BtSettings.ProfileConfig( 5523): Adding HeadsetClientService
,D/BtSettings.ProfileConfig( 5523): Adding A2dpSinkService
,D/BtSettings.ProfileConfig( 5523): Adding SapClientService
,D/BtSettings.ProfileConfig( 5523): Adding HidDevService
,I/BtSettings.ProfileConfig( 5523): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 1019): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
,D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1019): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,D/SettingsProvider( 1019): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1019): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,D/SettingsProvider( 1019): name = bt_svcst_com.android.bluetooth.hdp.HealthService
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
,D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1019): name = bt_svcst_com.android.bluetooth.pan.PanService
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1019): selectionArgs: false
,D/SettingsProvider( 1019): selectionArgs: 1002
,D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1019): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1019): name = bt_svcst_com.broadcom.bt.service.sap.SapService
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
,D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1019): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService,
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,D/SettingsProvider( 1019): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1019): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1019): selectionArgs: false
,D/SettingsProvider( 1019): selectionArgs: 1002
I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1019): name = bt_svcst_com.android.bluetooth.hid.HidDevService
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,D/BluetoothAdapterState( 5523): make
,I/bluedroid( 5523): init
,I/BluetoothAdapterState( 5523): Entering OffState
,I/bte_conf( 5523): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5523): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 5523): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5523): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 5523): btif_fetch_local_ble_random_bdaddr
,I/bluedroid( 5523): get_profile_interface socket
,I/bluedroid( 5523): get_profile_interface map_client
,D/BluetoothAdapterService( 5523): checkAddrForIOP: Loading from conf
,I/GKI_LINUX( 5523): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 5523): Address is:08:EC:A9:50:75:41
,E/BluetoothServiceJni( 5523): populateRssiValuesNative
,I/bluedroid( 5523): getModelRssiValues
E/BluetoothServiceJni( 5523): model_rssi_values_callback: low = -70, mid = -60, high = 127
,D/BluetoothAdapterProperties( 5523): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/SettingsProvider( 1019): name = bluetooth_name
,D/BluetoothAdapterProperties( 5523): Name is: A3-1
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/bluedroid( 5523): config_hci_snoop_log
,D/BluetoothManagerService( 1019): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothManagerService( 1019): Ble is always on enable gatt
,I/BluetoothManagerService( 1019): enableGattForLeMode, doBind called
,I/BtGatt.JNI( 5523): classInitNative(L900): classInitNative: Success!
,E/DevicePolicyManagerService( 1019): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1019): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider( 1019): uri = 3 selection = isBluetoothEnabled
,D/BluetoothManagerService( 1019): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/BluetoothAdapterState( 5523): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,D/BluetoothAdapterProperties( 5523): Setting state to 11
I/BluetoothAdapterState( 5523): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 5523): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5523): updateAdapterState state is 11
,D/BluetoothAdapterService( 5523): Autoconnection is available 
D/BluetoothAdapterService( 5523): updateAdapterState prevState = 10newState = 11
,D/BluetoothSecureManager( 5523): getInstant: null
W/InputMethodManagerService( 1019): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothSecureManager( 5523): calling getMethod for getService
,D/BluetoothSecureManager( 5523): calling getService
I/InputMethodManagerService( 1019): [BT Setting State] State =11
,D/BluetoothSecureManager( 5523): getService return binder: android.os.BinderProxy@2eb7ecc8
,D/BluetoothSecureManagerService( 1019): isSecureModeEnabled
,D/BluetoothSecureManagerService( 1019): getSecureModeSetting, name: secure_mode_enable
D/BtConfig.SecureMode( 5523): isSecureModeOn:false
D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 5523): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5523): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5523): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5523): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5523): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5523): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5523): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5523): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5523): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 5523): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5523): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 5523): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/BluetoothBondStateMachine( 5523): make
,D/BluetoothTile( 1179):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1179): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1179):  getBluetoothState : 11
,I/SamsungIME( 1763): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,W/BluetoothAdapterService( 5523): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5523): Not skipping com.android.bluetooth.gatt.GattService
I/BluetoothBondStateMachine( 5523): StableState(): Entering Off State
,D/StatusBarManagerService( 1019): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1019): setIconVisibility slot=bluetooth visible=false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
D/PhoneStatusBar( 1179): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5523): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5523): Not skipping com.android.bluetooth.hfp.HeadsetService
D/PhoneStatusBar( 1179): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,D/BtGatt.DebugUtils( 5523): handleDebugAction() action=null
,D/BtGatt.GattService( 5523): Received start request. Starting profile...
D/BtGatt.GattService( 5523): start()
D/BtGatt.GattService( 5523): start()
I/bluedroid( 5523): get_profile_interface gatt
,D/BluetoothAdapterService( 5523): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23574ef3
D/BtGatt.AdvertiseManager( 5523): advertise manager created
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothTile( 1179):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1179): onStateChanged: Bluetooth
,W/BluetoothAdapterService( 5523): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 5523): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/BtGatt.GattService( 5523): mStartError = false
D/BluetoothAdapterService( 5523): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23574ef3
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5523): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 5523): Not skipping com.android.bluetooth.hid.HidService
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5523): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5523): Not skipping com.android.bluetooth.hdp.HealthService
,D/HeadsetService( 5523): Received start request. Starting profile...
D/HeadsetService( 5523): start()
,D/BluetoothNotiBroadcastReceiver( 1302): onReceive
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothHeadsetServiceJni( 5523): classInitNative: succeeds
,D/HeadsetStateMachine( 5523): make
,W/BluetoothAdapterService( 5523): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5523): Not skipping com.android.bluetooth.pan.PanService
,E/HeadsetStateMachine( 5523): # of Max HF connection is 2
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/BluetoothAdapterService( 5523): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5523): Not skipping com.android.bluetooth.map.BluetoothMapService
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,V/BluetoothStatusReceiver( 1179): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1179): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,W/BluetoothAdapterService( 5523): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService,
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
W/BluetoothAdapterService( 5523): Not skipping com.broadcom.bt.service.sap.SapService
I/bluedroid( 5523): get_profile_interface handsfree
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5523): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5523): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5523): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService,
W/BluetoothAdapterService( 5523): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5523): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5523): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService,
W/BluetoothAdapterService( 5523): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5523): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 5523): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService,
I/BluetoothAdapterState( 5523): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 5566): MountEmulatedStorage()
I/libpersona( 5566): KNOX_SDCARD checking this for 10055
,E/Zygote  ( 5566): v2
I/libpersona( 5566): KNOX_SDCARD not a persona
,I/SELinux ( 5566): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5566): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5566): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1019): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5566 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,I/DualScoManager( 5523): Instantiating Dual Sco Manager
I/DualScoManager( 5523): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 5523): createCMTIContentObservers
,D/SettingsProvider( 1019): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,I/art     (  317): Explicit concurrent mark sweep GC freed 8711(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 26.253ms
,D/Tethering( 1019): interfaceAdded wlan0
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=1002,
,D/HeadsetStateMachine( 5523): Enter Disconnected: -2
,I/WifiHW  (  279): wifi_change_fw_path(): fwpath = sta
D/SoftapController(  279): Softap fwReload - Ok
,D/HeadsetService( 5523): mStartError = false
D/BluetoothAdapterService( 5523): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23574ef3
,E/BluetoothAdapterService(592924403)( 5523): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,D/BluetoothA2dp( 1019): Proxy object connected
,D/HeadsetStateMachine( 5523): Clear mHeadsetBrsf,
D/HeadsetStateMachine( 5523): map size, before remove : 0
D/HeadsetStateMachine( 5523): map size, after remove: 0
,E/Tethering( 1019): No numeric data
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 28.628ms
,D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1019): clearTetheredNotification()
D/A2dpService( 5523): Received start request. Starting profile...
D/A2dpService( 5523): start()
,I/BluetoothAvrcpServiceJni( 5523): classInitNative: succeeds
I/bluedroid( 5523): get_profile_interface avrcp
,D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false,
D/Tethering( 1019): InitialState.processMessage what=4,
I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
D/NtpTrustedTime( 1019): forceRefresh() from cache miss
,D/TimaKeyStoreProvider( 5566): TimaSignature is unavailable
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
D/CommandListener(  279): Setting iface cfg
D/CommandListener(  279): Trying to bring down wlan0
D/ActivityThread( 5566): Added TimaKeyStore provider
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000,
D/CommandListener(  279): Clearing all IP addresses on wlan0
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 17.522ms
D/NtpTrustedTime( 1019): forceRefresh Fail.
,D/Tethering( 1019): interfaceAdded p2p0,
E/Tethering( 1019): No numeric data
D/Tethering( 1019): p2p0 is not a tetherable iface, ignoring
D/Tethering( 1019): interfaceLinkStateChanged p2p0, false
V/NetworkStats( 1019): performPollLocked(flags=0x1)
D/Tethering( 1019): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1019): interfaceLinkStateChanged p2p0, false
,D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
,D/HotspotTile( 1179): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering( 1019): clearTetheredNotification()
D/HotspotTile( 1179): updateTetherState():false, false
,D/NtpTrustedTime( 1019): forceRefresh() from cache miss
,D/HotspotTile( 1179): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/NtpTrustedTime( 1019): forceRefresh Fail.
D/HotspotTile( 1179): updateTetherState():false, false
D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
V/NetworkStats( 1019): performPollLocked() took 7ms
D/NtpTrustedTime( 1019): forceRefresh() from cache miss
V/NetworkStats( 1019): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
D/NtpTrustedTime( 1019): forceRefresh Fail.
E/WifiHW  ( 1019): supplicant_name : p2p_supplicant
V/NetworkStats( 1019): performPollLocked() took 3ms
,D/NtpTrustedTime( 1019): forceRefresh() from cache miss
D/NtpTrustedTime( 1019): forceRefresh Fail.
,D/UserAnalysis.PlaceProvider( 5566): PlaceProvider onCreate()
,D/UserAnalysis.SecureDbManager( 5566): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5566): SecurePlaceDbHelper() 
D/UserAnalysis( 5566): Create SecureDbHelper
,D/IntelligenceServiceApplication( 5566): onCreate(),
,E/RemoteController( 5523): Cannot set synchronization mode on an unregistered RemoteController
,I/ActivityManager( 1019): Killing 4896:com.wssyncmldm/1000 (adj 15): empty #31
,D/WifiMonitor( 1019): startMonitoring(wlan0) with mConnected = false
,D/IntelligenceServiceApplication( 5566): no applications having user consent for prediction
,I/Avrcp   ( 5523):  Updating now playing list upon AVRCP Start
,D/BluetoothMediaBrowser( 5523):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/BluetoothA2dpServiceJni( 5523): classInitNative: succeeds
D/A2dpStateMachine( 5523): make
,I/bluedroid( 5523): get_profile_interface a2dp
,I/GKI_LINUX( 5523): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 5523): warning : media task started media_task_refcnt 1 
D/A2dpService( 5523): mStartError = false
D/BluetoothAdapterService( 5523): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23574ef3
D/A2dpStateMachine( 5523): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 5523): classInitNative: succeeds
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/HotspotTile( 1179): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1179): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1179): Wifi onReceive(2)
I/wpa_supplicant( 5586): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 5586): Successfully initialized wpa_supplicant,
D/STATUSBAR-QSTileView( 1179): onStateChanged: Wi-Fi,
D/HotspotTile( 1179): onReceive : 2, 0
,D/HidService( 5523): Received start request. Starting profile...
D/HidService( 5523): start()
I/bluedroid( 5523): get_profile_interface hidhost
D/HidService( 5523): setHidService(): set to: null
D/HidService( 5523): mStartError = false
D/BluetoothAdapterService( 5523): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23574ef3
,I/BluetoothHealthServiceJni( 5523): classInitNative: succeeds
,I/SecureStorage( 5586): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
D/HealthService( 5523): Received start request. Starting profile...
D/HealthService( 5523): start()
,I/bluedroid( 5523): get_profile_interface health
D/HealthService( 5523): mStartError = false,
D/BluetoothAdapterService( 5523): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23574ef3
V/PlaceDetection v1.0.19 ( 5566): [PlaceDetection::stopService] Service stopped.
,I/SecureStorage( 5586): [INFO]: SPID(0x00000000)This device supports Secure Storage
D/WifiCredService( 1302): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/BluetoothMediaBrowser( 5523): no now playing list
D/BluetoothMediaBrowser( 5523):  getNowPlayingId now playing id : -1
,I/SecureStorage(  397): [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 5586
I/SecureStorage(  397): [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
,I/SecureStorage( 5586): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 5586): ssSupport state is = 1
,I/wpa_supplicant( 5586): >>>>> GET KEY, IV <<<<<
I/SecureStorage( 5586): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  397): [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 5586
I/SecureStorage(  397): [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
I/BluetoothPanServiceJni( 5523): classInitNative(L105): succeeds
,D/PanService( 5523): Received start request. Starting profile...,
D/PanService( 5523): start()
D/BluetoothPanServiceJni( 5523): initializeNative(L110): pan
I/bluedroid( 5523): get_profile_interface pan
D/PanService( 5523): mStartError = false
D/BluetoothAdapterService( 5523): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23574ef3
,V/PlaceDetection v1.0.19 ( 5566): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/BluetoothPan( 1019): BluetoothPAN Proxy object connected
,D/BluetoothMapService( 5523): Received start request. Starting profile...
,D/BluetoothMapService( 5523): start()
,D/BluetoothMapService( 5523): mStartError = false
D/BluetoothAdapterService( 5523): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23574ef3
D/HeadsetStateMachine( 5523): Try to query the phonestate on bind
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4896/cgroup.procs: No such file or directory
,I/Telecom ( 1429): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1429): BluetoothPhoneService: handleMessage(7) / param 0
,I/Telecom ( 1429): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 1429): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,I/Telecom ( 1429): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,I/Telecom ( 1429): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 1429): Proxy not attached to service
,I/Telecom ( 1429): BluetoothPhoneService: Result of Message : true
,D/HeadsetStateMachine( 5523): Proxy object connected
D/HeadsetPhoneState( 5523): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
I/BluetoothSAPServiceJni( 5523): classInitNative(L204): succeeds
,D/HeadsetStateMachine( 5523): Disconnected process message: 11
,D/SapService( 5523): Received start request. Starting profile...
,D/SapService( 5523): start()
D/BluetoothSAPServiceJni( 5523): initializeNative(L209): sap
,I/bluedroid( 5523): get_profile_interface sap
D/SapService( 5523): mStartError = false
D/BluetoothAdapterService( 5523): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23574ef3
D/HeadsetPhoneState( 5523): sendDeviceDataStateChanged
,D/HeadsetPhoneState( 5523): Signal level : previous=0 curr=0
,V/HeadsetService( 5523): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
E/BluetoothAdapterService(592924403)( 5523): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothA2dp( 5523): Proxy object connected
D/HeadsetStateMachine( 5523): Disconnected process message: 18
D/BluetoothAdapterService( 5523): Bluetooth A2dp source service connected
D/HeadsetStateMachine( 5523): Disconnected process message: 10
D/HeadsetPhoneState( 5523): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5523): Disconnected process message: 11
E/BluetoothAdapterService(592924403)( 5523): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/BluetoothAdapterService(592924403)( 5523): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(592924403)( 5523): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,D/AuthorizationBluetoothService( 1657): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/BluetoothAdapterService(592924403)( 5523): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5594): MountEmulatedStorage()
,E/Zygote  ( 5594): v2
I/libpersona( 5594): KNOX_SDCARD checking this for 10141
I/libpersona( 5594): KNOX_SDCARD not a persona
,I/SELinux ( 5594): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=5594 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/SELinux ( 5594): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 5594): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Hs20UtilService( 3389): Starting #2
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/Hs20UtilService( 3389): Message received 5011
,E/Zygote  ( 5604): MountEmulatedStorage(),
I/libpersona( 5604): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5604): v2
,I/libpersona( 5604): KNOX_SDCARD not a persona
,I/SELinux ( 5604): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5604): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 5604): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=5604 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5594): TimaSignature is unavailable
,D/ActivityThread( 5594): Added TimaKeyStore provider
,W/ResourcesManager( 5594): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5594): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5594): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5594): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 5604): TimaSignature is unavailable
D/ActivityThread( 5604): Added TimaKeyStore provider
I/SecureStorage(  397): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,I/SecureStorage( 5586): [INFO]: SPID(0x00000001)Processing data has been completed
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 5604): KnoxConfiguration : Current State = 1
I/wpa_supplicant( 5586): Ctrl_iface: loading cred from phone
,I/SecureStorage( 5586): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,E/BluetoothAdapterService(592924403)( 5523): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,E/BluetoothAdapterService(592924403)( 5523): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,I/ActivityManager( 1019): Killing 4917:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31,
,I/SecureStorage( 5586): [INFO]: SPID(0x00000001)This device supports Secure Storage
,D/BluetoothAdapterState( 5523): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 5523): enable
I/SecureStorage(  397): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5586
I/SecureStorage(  397): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5586): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5586): ssSupport state is = 1
D/SecurityLogAgent( 5604): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 5604): StateMachine : Current State = 1
,I/bt_hci_bdroid( 5523): init
,I/wpa_supplicant( 5586): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
I/GKI_LINUX( 5523): gki_task_entry task_id=0 [BTU] starting
,E/wpa_supplicant( 5586): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5586): SIM READ ERROR
I/wpa_supplicant( 5586): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5586): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5586): SIM READ ERROR
I/wpa_supplicant( 5586): Blacklist: Clear (all) 
I/wpa_supplicant( 5586): wpa_default_ap_write_once
I/wpa_supplicant( 5586): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5586): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5586): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 5586): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5586): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,D/SecurityLogAgent( 5604): StateMachine : Changed Current State = 1
,I/wpa_supplicant( 5586): rfkill: Cannot open RFKILL control device
,I/ActivityManager( 1019): Killing 3956:com.sec.spp.push/u0a32 (adj 15): empty #31
,D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1019): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
,I/bt_vendor( 5523): bt-vendor : init
,I/bt_vendor( 5523): bt-vendor : get_bt_soc_type
E/bt_vendor( 5523): get_bt_soc_type: Failed to get soc type
,I/bt_vendor( 5523): init: Local BD Address : 41:75:50:a9:ec:08
D/bt_userial_mct( 5523): userial_init
,I/bt_vendor( 5523): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 5523): Starting hciattach daemon
I/bt_vendor( 5523): try to set false
I/bt_vendor( 5523): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 5523): Starting hciattach daemon
I/bt_vendor( 5523): try to set true
,I/qcom-bluetooth( 5637): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,I/wpa_supplicant( 5586): wlan0: Setting scan request: 0 sec 100000 usec
,I/qcom-bluetooth( 5644): /system/etc/init.qcom.bt.sh: Transport : smd ,
,I/qcom-bluetooth( 5645): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,I/qcom-bluetooth( 5647): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,I/qcom-bluetooth( 5648): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,I/qcom-bluetooth( 5649): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,I/qcom-bluetooth( 5650): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,W/libprocessgroup( 1019): failed to open /acct/uid_10032/pid_3956/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10139/pid_4917/cgroup.procs: No such file or directory
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 44135(2MB) AllocSpace objects, 34(544KB) LOS objects, 33% free, 23MB/35MB, paused 2.750ms total 166.104ms,
,I/wpa_supplicant( 5586): wlan0: State: DISCONNECTED -> DISCONNECTED
I/SecureStorage( 5586): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,D/BadgeProvider( 5185): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/SecureStorage( 5586): [INFO]: SPID(0x00000001)This device supports Secure Storage,
I/SecureStorage(  397): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5586
I/SecureStorage(  397): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5586): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5586): ssSupport state is = 1
,I/wpa_supplicant( 5586): Ctrl_iface: loading cred from phone
,I/SecureStorage( 5586): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,I/SecureStorage( 5586): [INFO]: SPID(0x00000001)This device supports Secure Storage,
I/SecureStorage(  397): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5586
I/SecureStorage(  397): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
D/BadgeProvider( 5185): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5185): sendNotify, [notify] : null,
D/BadgeProvider( 5185): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5185): update, [BadgeCount] : badgecount=0,
D/BadgeProvider( 5185): update, [UpdateCount] : 1
I/SecureStorage( 5586): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5586): ssSupport state is = 1
I/wpa_supplicant( 5586): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant( 5586): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5586): SIM READ ERROR
I/wpa_supplicant( 5586): wpa_default_ap_write_once
I/wpa_supplicant( 5586): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5586): rfkill: Cannot open RFKILL control device
D/Launcher.Model( 1478): reloadBadges entered.
,D/Tethering( 1019): interfaceLinkStateChanged p2p0, false
D/Tethering( 1019): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1019): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1019): interfaceLinkStateChanged p2p0, false
D/Tethering( 1019): interfaceStatusChanged p2p0, false
,I/Nat464Xlat( 1019): interfaceLinkStateChanged p2p0, false
,W/ActivityManager( 1019): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/wpa_supplicant( 5586): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 5586): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 5586): p2p0: State: INACTIVE -> DISCONNECTED,
,I/wpa_supplicant( 5586): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 5586): Skip scan - bUseNetwork false
,E/WifiStateMachine( 1019): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 5586): HOTSPOT20_ENABLE called
I/wpa_supplicant( 5586): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5586): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5586): SIM READ ERROR
I/wpa_supplicant( 5586): Blacklist: Clear (all) 
,I/wpa_supplicant( 5586): wlan0: Setting scan request: 0 sec 0 usec,
,I/wpa_supplicant( 5586): Skip scan - bUseNetwork false
,D/WifiNative-wlan0( 1019): callSECApiInt - ID [210]
,D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiConfigStore( 1019): Loading config and enabling all networks 
,D/STATUSBAR-WifiQuickSettingButton( 1179): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1179): Wifi onReceive(3)
,D/HotspotTile( 1179): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1179): onStateChanged: Wi-Fi
,D/HotspotTile( 1179): onReceive : 3, 0
,D/WifiCredService( 1302): Action received :android.net.wifi.WIFI_STATE_CHANGED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3389): Starting #3
,I/Hs20UtilService( 3389): Message received 5011
,D/SecurityLogAgent( 5604): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5604): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5604): StateMachine : Current State = 1
D/SecurityLogAgent( 5604): StateMachine : Changed Current State = 1
,I/qcom-bluetooth( 5660): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:75:41 
,E/WifiConfigStore( 1019): Not a HS20
,E/WifiConfigStore( 1019): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-wlan0( 1019): callSECApiInt - ID [65]
,D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 5586): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 5586): wlan0: Setting scan request: 8 sec 0 usec,
I/wpa_supplicant( 5586): reset timer : RESET_TIMER 0
I/wpa_supplicant( 5586): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 5586): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 5586): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5586): First Scan Start
I/wpa_supplicant( 5586): Scan requested (ret=0) - scan timeout 30 seconds,
,D/WifiNative-wlan0( 1019): Setting external_sim to 1
I/qcom-bluetooth( 5661): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,D/WifiStateMachine( 1019): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1019): startHal
E/wifi    ( 1019): getStaticLongField sWifiHalHandle 0x9d80d88c
I/WifiNative-HAL( 1019): Could not start hal
,D/Tethering( 1019): interfaceLinkStateChanged p2p0, false,
I/Nat464Xlat( 1019): interfaceLinkStateChanged p2p0, false
D/Tethering( 1019): interfaceStatusChanged p2p0, false
,W/Settings( 5387): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiNative-wlan0( 1019): do suspend true,
E/WifiStateMachine( 1019): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiP2pService( 1019): P2pDisabledState{ what=131203 }
,D/WifiScanningService( 1019): SCAN_AVAILABLE : 3
E/WifiStateMachine( 1019): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1019): callSECStringApiVoid - ID [215]
,E/WifiNative-wlan0( 1019): invaild command id : 215
D/WifiScanningService( 1019): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1019): startHal
E/wifi    ( 1019): getStaticLongField sWifiHalHandle 0x9eb4d9bc
I/WifiNative-HAL( 1019): Could not start hal
E/WifiScanningService( 1019): could not start HAL,
D/RttService( 1019): SCAN_AVAILABLE : 3
D/CommandListener(  279): Setting iface cfg
D/RttService( 1019): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler },
D/CommandListener(  279): Trying to bring up p2p0
,D/WifiP2pService( 1019): P2pEnablingState
E/WifiStateMachine( 1019): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1019): callSECStringApiVoid - ID [215],
E/WifiNative-wlan0( 1019): invaild command id : 215
D/WifiMonitor( 1019): startMonitoring(p2p0) with mConnected = true
I/wpa_supplicant( 5586): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,I/wpa_supplicant( 5586): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/wpa_supplicant( 5586): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine( 1019): Failed to set frequency band 0,
,D/WifiP2pService( 1019): P2pEnablingState{ what=147457 }
,D/WifiP2pService( 1019): P2p socket connection successful
,I/bt_vendor( 5523): bluetooth satus is on
D/WifiP2pService( 1019): P2pEnabledState
D/bt_userial_mct( 5523): userial_open(port:0)
I/bt_vendor( 5523): bt-vendor : BT_VND_OP_USERIAL_OPEN
,I/bt_vendor( 5523): Done intiailizing UART
,D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
I/bt_vendor( 5523): Done intiailizing UART
I/bt_userial_mct( 5523): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
I/bt_vendor( 5523): Bluetooth Firmware and transport layer are initialized
,D/WifiP2pService( 1019): sending p2p connection changed broadcast: IDLE
,D/bt_userial_mct( 5523): Entering userial_read_thread()
,E/WifiStateMachine( 1019): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController( 1019): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled,
D/SecContentProvider2( 1019): mCursor = null
,D/WifiP2pService( 1019): create mNetworkAgent
,D/WifiDisplayController( 1019): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1019): disconnect
D/WifiDisplayController( 1019): updateConnection
D/WifiDisplayController( 1019): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1179): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1179): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/ConnectivityService( 1019): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1019): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 1019): updateNetworkInfo()
,D/ConnectivityService( 1019): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/CSLegacyTypeTracker( 1019): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,D/WifiNative-p2p0( 1019): p2pGetDeviceAddress
,D/WifiNative-p2p0( 1019): p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,D/WifiDisplayController( 1019): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/        ( 5523): BTE_InitTraceLevels -- TRC_HCI
,D/WifiP2pService( 1019): DeviceAddress: 0a:75:42
I/        ( 5523): BTE_InitTraceLevels -- TRC_L2CAP
D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
I/        ( 5523): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5523): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 5523): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5523): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5523): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5523): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5523): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5523): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5523): BTE_InitTraceLevels -- TRC_SAP
I/        ( 5523): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5523): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5523): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5523): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5523): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 5523): BTE_InitTraceLevels -- TRC_PROTOCOL
,D/WifiDisplayController( 1019): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A3-1
D/WifiDisplayController( 1019):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiDisplayController( 1019):  primary type: 10-0050F204-5
D/WifiDisplayController( 1019):  secondary type: null
D/WifiDisplayController( 1019):  wps: 0
D/WifiDisplayController( 1019):  grpcapab: 0
D/WifiDisplayController( 1019):  devcapab: 0
D/WifiDisplayController( 1019):  status: 3
D/WifiDisplayController( 1019):  wfdInfo: null
D/WifiDisplayController( 1019):  groupownerAddress: null
D/WifiDisplayController( 1019):  GOdeviceName: null
D/WifiDisplayController( 1019):  interfaceAddress: 
D/WifiDisplayController( 1019):  SConnectInfo : null
,V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
,I/ActivityManager( 1019): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=5667 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 5667): MountEmulatedStorage()
E/Zygote  ( 5667): v2
I/libpersona( 5667): KNOX_SDCARD checking this for 10064
I/libpersona( 5667): KNOX_SDCARD not a persona
,I/SELinux ( 5667): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/WifiP2pService( 1019): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 1019): InactiveState
I/SELinux ( 5667): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/WifiP2pService( 1019): InactiveState{ what=143376 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=143376 }
E/SELinux ( 5667): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/wpa_supplicant( 5586): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/WifiP2pService( 1019): InactiveState{ what=143376 }
E/ConnectivityService( 1019): updateNetworkInfo()
D/WifiP2pService( 1019): P2pEnabledState{ what=143376 }
,D/TimaKeyStoreProvider( 5667): TimaSignature is unavailable
,D/ActivityThread( 5667): Added TimaKeyStore provider
,W/ResourcesManager( 5667): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/bt-l2cap( 5523): l2c_link_processs_ble_num_bufs 16
,E/bt-btm  ( 5523): BTM_SecRegister:p_cb_info->p_le_callback == 0xa4461ead ,
E/bt-btm  ( 5523): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4461ead 
,D/FileShare-Client( 5667): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Client( 5667): ClientBroadcastReceiver.onReceive - disconnected,
,D/BluetoothAdapterProperties( 5523): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,E/bt-btif ( 5523): AG evt (hdl 0x00010,
E/bt-btif ( 5523): btif_storage_get_adapter_property service_mask:0x2120048
D/BluetoothAdapterProperties( 5523): Address is:08:EC:A9:50:75:41,
E/BluetoothServiceJni( 5523): populateRssiValuesNative,
I/bluedroid( 5523): getModelRssiValues
E/BluetoothServiceJni( 5523): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5523): modelRssiValuesCallback, low, mid, high = -70,-60,127
D/BluetoothAdapterProperties( 5523): Name is: A3-1
D/SettingsProvider( 1019): name = bluetooth_name
,D/BluetoothAdapterProperties( 5523): Scan Mode:20
,D/BluetoothAdapterProperties( 5523): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 5523): LE Address is:C8:D9:53:A0:EA:82
,E/bt-btif ( 5523): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,E/bt-btif ( 5523): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt_mct  ( 5523): hci lib postload completed
,E/bt-btif ( 5523): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 5523): btif_sock_init: !vhci_init
,D/IOP_DB_BT( 5523): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT( 5523): db_open: db_open : handle 3028451344l, read 13894 bytes onto local cache
,D/IOP_DB_BT( 5523): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,D/IOP_DB_BT( 5523): db_query: result 1
I/        ( 5523): iop_db_open: iop_db_open status 0
,D/bte_conf( 5523): Device ID record 1 : primary
,D/bte_conf( 5523):   vendorId            = 0075
D/bte_conf( 5523):   vendorIdSource      = 0001
D/bte_conf( 5523):   product             = 0100
D/bte_conf( 5523):   version             = 0200
D/bte_conf( 5523):   clientExecutableURL = 
D/bte_conf( 5523):   serviceDescription  = 
D/bte_conf( 5523):   documentationURL    = 
D/bte_conf( 5523): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 5523): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 5523): ScanMode =  20
,D/BluetoothAdapterProperties( 5523): State =  11,
D/SecContentProvider( 1019): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties( 5523): Setting state to 12
I/BluetoothAdapterState( 5523): Bluetooth adapter state changed: 11-> 12
,D/BluetoothPanServiceJni( 5523): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterProperties( 5523): Scan Mode:21
,D/BluetoothAdapterProperties( 5523): Discoverable Timeout:120
D/SettingsProvider( 1019): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
,D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 5523): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5523): updateAdapterState state is 12
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/FileShare-Client( 5667): Outbound.stopDelayTimer - 
,D/BluetoothA2dp( 1019): onBluetoothStateChange: up=true
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
I/BluetoothPbapService( 5523): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
I/BluetoothPbapService( 5523): Handler(): got msg=1
,D/SecContentProvider( 1019): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
D/BluetoothAdapterService( 5523): Autoconnection is available 
D/BluetoothAdapterService( 5523): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 5523): starting service from this receiver
,D/BluetoothAdapter( 5473): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5473): onBluetoothStateChange: Bluetooth is on
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/BluetoothAdapter( 1179): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1179): onBluetoothStateChange: Bluetooth is on
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/BluetoothAdapter( 1667): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1667): onBluetoothStateChange: Bluetooth is on
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/BluetoothA2dp( 5523): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1442): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1442): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1019): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1019): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 5523): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 5523): onBluetoothStateChange: Bluetooth is on
,E/Zygote  ( 5685): MountEmulatedStorage(),
E/Zygote  ( 5685): v2
I/libpersona( 5685): KNOX_SDCARD checking this for 10065
D/BluetoothAdapter( 1429): onBluetoothStateChange: up=true
I/libpersona( 5685): KNOX_SDCARD not a persona
D/BluetoothAdapter( 1429): onBluetoothStateChange: Bluetooth is on
,I/SELinux ( 5685): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/BluetoothAdapter( 1452): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1452): onBluetoothStateChange: Bluetooth is on
,I/ActivityManager( 1019): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5685 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5685): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5685): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Killing 4601:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,V/BluetoothPbapService( 5523): PBAP Service initSocket try: 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothAdapterState( 5523): Entering On State from state = 11
,W/InputMethodManagerService( 1019): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1019): [BT Setting State] State =12
I/InputMethodManagerService( 1019): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,W/BluetoothAdapter( 5523): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothTile( 1179):  onBluetoothStateChange:
,D/BluetoothHeadset( 1429): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3d12b441, true
,D/BluetoothHeadset( 1429): registerMessageListener
,D/BluetoothTile( 1179):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1179): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1179):  getBluetoothState : 12
,D/TimaKeyStoreProvider( 5685): TimaSignature is unavailable
,D/ActivityThread( 5685): Added TimaKeyStore provider
,D/BluetoothTile( 1179):  handleUpdatestate:false name:null
,D/BluetoothSocket( 5523): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,D/BluetoothSocket( 5523): bindListen(), new LocalSocket 
D/BluetoothSocket( 5523): bindListen(), new LocalSocket.getInputStream() 
I/SamsungIME( 1763): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothSocket( 5523): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22a8aa79
,D/BluetoothSocket( 5523): channel: 19
D/HeadsetService( 5523): registerMessageListener
,D/BluetoothPbapService( 5523): PBAP Socket is BluetoothServerSocket
,D/HeadsetService( 5523): registerMessageListener
D/HeadsetStateMachine( 5523): Disconnected process message: 70
,I/Telecom ( 1429): BluetoothPhoneService: handleMessage(7) / param null
I/Telecom ( 1429): BluetoothPhoneService: updateHeadsetWithCallState
,D/HeadsetStateMachine( 5523): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@28a8b6c
,D/StatusBarManagerService( 1019): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1019): setIconVisibility slot=bluetooth visible=true
,D/PhoneStatusBar( 1179): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,I/Telecom ( 1429): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
I/Telecom ( 1429): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
I/Telecom ( 1429): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothTile( 1179):  handleUpdatestate:false name:null
,D/HeadsetStateMachine( 5523): Disconnected process message: 9
,D/HeadsetStateMachine( 5523): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/BluetoothTile( 1179):  handleUpdatestate:false name:null
,D/BluetoothMapMasInstance( 5523): set MAP SDP message type : 1
,D/audio_hw_primary(  284): adev_set_parameters: enter: A2dpSuspended=false
,V/voice   (  284): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  284): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  284): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  284): adev_set_parameters: exit
,E/HeadsetStateMachine( 5523): terminateScoUsingVirtualVoiceCall:No present call to terminate
,W/BluetoothAdapter( 5523): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5523): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
D/BluetoothSocket( 5523): bindListen(), new LocalSocket 
D/BluetoothSocket( 5523): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5523): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@8e63dca
,D/BluetoothSocket( 5523): channel: 5
,W/libprocessgroup( 1019): failed to open /acct/uid_10032/pid_4601/cgroup.procs: No such file or directory
,E/SMD     (  292): DCD OFF
,D/FileShare-Server( 5685): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 1019): Killing 5028:com.samsung.helphub/1000 (adj 15): empty #31
,W/ContextImpl( 1302): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/LocalBluetoothProfileManager( 1302): Adding local A2DP profile
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1302): Adding local HEADSET profile
,E/BluetoothHeadset( 1302): BTStateChangeCB is registed
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 1302): BluetoothHeadset service is binded
,D/BluetoothMap( 1302): Create BluetoothMap proxy object
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ContextImpl( 1302): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/Bluetoothsap( 1302): bindService called to Bluetooth SAP Service
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1302): PANU : true
,W/LocalBluetoothProfileManager( 1302): Warning: SAP profile was previously added.
,D/LocalBluetoothProfileManager( 1302): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1302): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1302): onReceive
,D/BluetoothA2dp( 1302): Proxy object connected
D/A2dpProfile( 1302): Bluetooth service connected
,V/BluetoothStatusReceiver( 1179): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1179): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
D/HeadsetProfile( 1302): Bluetooth service connected
,D/BluetoothMap( 1302): Proxy object connected
,D/MapProfile( 1302): Bluetooth service connected
D/BluetoothMap( 1302): getConnectedDevices()
,D/BluetoothAdapterService( 5523): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23574ef3
,D/BtConfig.SecureMode( 5523): isSecureModeOn:false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothPbap( 1302): Proxy object connected
D/PbapServerProfile( 1302): Bluetooth service connected
D/Bluetoothsap( 1302): BluetoothSAP Proxy object connected
D/SapProfile( 1302): Bluetooth service connected
D/Bluetoothsap( 1302): getConnectedDevices()
,D/BluetoothInputDevice( 1302): Proxy object connected
D/HidProfile( 1302): Bluetooth service connected
,D/AuthorizationBluetoothService( 1657): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothPan( 1302): BluetoothPAN Proxy object connected
D/PanProfile( 1302): Bluetooth service connected
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5028/cgroup.procs: No such file or directory
,D/SecContentProvider( 1019): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/BluetoothAdapter( 5523): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5523): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,D/BluetoothSocket( 5523): bindListen(), new LocalSocket 
D/BluetoothSocket( 5523): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5523): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a8dc04
D/BluetoothSocket( 5523): channel: 12
I/BtOppRfcommListener( 5523): Accept thread started.
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1399): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1399): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5523): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5523): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1179): level :100 plugged : 2
,I/wpa_supplicant( 5586): nl80211: Received scan results (4 BSSes),
I/wpa_supplicant( 5586): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 5586): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 5586): Trying to associate with  'G700'
I/wpa_supplicant( 5586): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 5586): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1019): didn't find BSSID Trying to associate with SSID 'NG700',
I/WifiNative-HAL( 1019): startHal
E/wifi    ( 1019): getStaticLongField sWifiHalHandle 0x9d80d8ac
I/WifiNative-HAL( 1019): Could not start hal
,D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
,I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb851e7c8
I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1202591608)
,E/wpa_supplicant( 5586): Cmd 35605 not handled,
I/wpa_supplicant( 5586): wlan0: State: ASSOCIATING -> ASSOCIATED
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 5586): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 5586): Associated with C0.AA.48
I/wpa_supplicant( 5586): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 5586): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE,
I/wpa_supplicant( 5586): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false
,D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1019): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1019): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
,I/wpa_supplicant( 5586): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 5586): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 5586): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 5586): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 5586): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5586): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 5586): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=],
I/wpa_supplicant( 5586): Blacklist: Clear (temp) 
I/wpa_supplicant( 5586): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1019): interfaceLinkStateChanged wlan0, true,
D/Tethering( 1019): interfaceStatusChanged wlan0, true
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1019): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1019): interfaceStatusChanged wlan0, true
,E/Tethering( 1019): No numeric data
,I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, true
D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1019): clearTetheredNotification()
,D/NtpTrustedTime( 1019): forceRefresh() from cache miss
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
,D/HotspotTile( 1179): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
D/HotspotTile( 1179): updateTetherState():false, false
D/NtpTrustedTime( 1019): forceRefresh Fail.
V/NetworkStats( 1019): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
V/NetworkStats( 1019): performPollLocked() took 4ms
D/NtpTrustedTime( 1019): forceRefresh() from cache miss
D/NtpTrustedTime( 1019): forceRefresh Fail.
D/WifiNative-wlan0( 1019): callSECApiVoid - ID [50]
E/WifiConfigStore( 1019): setLastSelectedConfiguration -1
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1202591608) wakelock released: 1, error no: 0
I/rmt_storage(  273): 
I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb851e7c8
D/ConnectivityService( 1019): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1019): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService( 1019): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1019): updateNetworkInfo()
D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/WifiConfigStore( 1019): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/Hs20UtilService( 3389): Starting #4
E/WifiConfigStore( 1019): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Hs20UtilService( 3389): Message received 5007
V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1302): MountReceiver.mPrefHandler - 7002
D/CommandListener(  279): Setting iface cfg
E/WifiStateMachine( 1019): Start Dhcp Watchdog 1
D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
E/WifiNative-wlan0( 1019): do suspend false
D/WifiP2pService( 1019): InactiveState{ what=143375 }
D/WifiP2pService( 1019): P2pEnabledState{ what=143375 }
E/dhcpcd  ( 5714): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 5714): version 5.5.6 starting
E/dhcpcd  ( 5714): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 5714): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 5714): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 5714): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 5714): bssid match
I/dhcpcd  ( 5714): wlan0: rebinding lease of 192.168.1.132
I/dhcpcd  ( 5714): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
I/dhcpcd  ( 5714): wlan0: leased 192.168.1.132 for 86400 seconds
E/WifiNative-wlan0( 1019): do suspend true
D/WifiP2pService( 1019): InactiveState{ what=143375 }
D/WifiP2pService( 1019): P2pEnabledState{ what=143375 }
D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/WifiStateMachine( 1019): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1019): VerifyingLinkState enter
D/WifiNative-wlan0( 1019): callSECApiInt - ID [210]
E/ConnectivityService( 1019): updateNetworkInfo()
D/ConnectivityService( 1019): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1019): Adding iface wlan0 to network 502
D/WifiWatchdogStateMachine( 1019): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 1019): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1019): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1019): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 1019): Adding Route [fe80::/64 -> :: wlan0] to network 502
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1019): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 1019): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1019): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
E/ConnectivityService( 1019): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1019): Setting Dns servers for network 502 to [/192.168.1.1]
D/ConnectivityService( 1019): LTETest block dns file not exists
D/ConnectivityService( 1019): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
E/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
E/ConnectivityService( 1019): updateNetworkInfo()
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 3389): Starting #5
I/Hs20UtilService( 3389): Message received 5007
I/WifiTrafficPoller( 1019): evaluateTrafficStatsPolling
E/ConnectivityService( 1019): updateNetworkInfo()
D/ConnectivityService( 1019): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1019): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1019): rematching NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
D/ConnectivityService( 1019):    accepting network in place of null
D/WIFI_P2P( 1019): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1019): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/TelephonyNetworkFactory( 1452): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1452): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/StatusBar.NetworkController( 1179): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/CSLegacyTypeTracker( 1019): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1019): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/System.out( 1019): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1019): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1019): (HTTPLog)-Static: isShipBuild true
I/System.out( 1019): (HTTPLog)-Thread-170-423568011: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1019): (HTTPLog)-Static: isSBSettingEnabled false
D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 1000
D/WIFI    ( 1019): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/ConnectivityService( 1019): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
I/WifiTrafficPoller( 1019): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1019): mBoosterFLAG : 0
I/WifiTrafficPoller( 1019): current booster mode : FullMode
D/ConnectivityService( 1019): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/WifiNative-wlan0( 1019): callSECApiVoid - ID [212]
D/EntConnectivity( 1019): Not allowed due to - mEnabled false - primarySimSlot false
D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524290
I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/Tethering( 1019): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/Tethering( 1019): MasterInitialState.processMessage what=3
V/NetworkStats( 1019): updateIfacesLocked()
V/NetworkStats( 1019): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
D/NtpTrustedTime( 1019): forceRefresh() from cache miss
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 1000
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/NetworkStats( 1019): performPollLocked() took 6ms
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): EthernetConnected: false
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1179): updateDataNetType()
D/StatusBar.NetworkController( 1179): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1179): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 1179): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 3389): Starting #6
I/Hs20UtilService( 3389): Message received 5007
D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1302): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1302): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3389): Starting #7
,D/NearbySettings( 1302): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1302): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 3389): Message received 5007
,D/WifiStateMachine( 1019): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/System.out( 1019): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1019): mCursor = null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 12:37:42 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449751062382], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449751062358]}
,E/Watchdog( 1019): !@Sync 5
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Validated
D/ConnectivityService( 1019): Validated NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1019): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1019): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,D/ConnectivityService( 1019): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524290
,I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1019): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019
,D/SRIB_DCS( 1179): log_dcs ThreadedRenderer::initialize entered! 
,D/StatusBar.NetworkController( 1179): EthernetConnected: false
,D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1179): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1179): updateDataNetType()
,D/StatusBar.NetworkController( 1179): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1179): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1179): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1179): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1019): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1449751063015 mCachedNtpElapsedRealtime : 168251 mCachedNtpCertainty : 10,
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1019): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 5075): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5075): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5075): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5075): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,I/splitIntent( 1019): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
D/AlarmManagerService( 1019): Setting time of day to sec=1449751063
I/splitIntent( 1019): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
D/AlarmManagerService( 1019): Trying to open a file
I/splitIntent( 1019): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,D/AlarmManagerService( 1019): File Open Success
D/AlarmManagerService( 1019): File Close Success
I/AlarmManagerService( 1019): DRM_TIME_PATH CHMOD 666 for resetState done 
V/AlarmManager( 1019): waitForAlarm result :65536
W/AlarmManagerService( 1019): Unable to set rtc to 1449751063: Invalid argument
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5755): MountEmulatedStorage()
E/Zygote  ( 5755): v2
I/libpersona( 5755): KNOX_SDCARD checking this for 10108
I/libpersona( 5755): KNOX_SDCARD not a persona
,I/SELinux ( 5755): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5755): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5755): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5755 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiStateMachine( 1019): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,I/DowntimeConditions( 1019): android.intent.action.TIME_SET ignored because schedule turned off.
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_SET
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 5755): TimaSignature is unavailable
,D/ActivityThread( 5755): Added TimaKeyStore provider
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/Settings( 1019): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/GpsLocationProvider( 1019): No APN found to select.
V/AlarmManager( 1019): waitForAlarm result :4
V/AlarmManager( 1019): No more alarm at this time.nowELAPSED=168599 batch.start=182821
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SettingsProvider( 1019): name = lockscreen_zoom_panning_effect
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10049
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,D/KeyguardEffectViewUtil( 1179): isStrongPowerSavingMode() :false
,D/KeyguardEffectViewController( 1179): isPreloadedWallpaper=true
I/GeometricMosaic_Keyguard( 1179): update
,I/DrmEventService( 1019):  no response from SecureClock 
,D/KeyguardEffectViewUtil( 1179): getCurrentWallpaper() mWallpaperPath :null
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5773): MountEmulatedStorage()
E/Zygote  ( 5773): v2
I/libpersona( 5773): KNOX_SDCARD checking this for 10071
I/libpersona( 5773): KNOX_SDCARD not a persona
,I/SELinux ( 5773): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=5773 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5773): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5773): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5773): TimaSignature is unavailable
D/ActivityThread( 5773): Added TimaKeyStore provider
,I/MusicStore( 5755): Database version: 120
,I/KeyguardEffectViewUtil( 1179): set current wallpaper info,
D/SettingsProvider( 1019): name = keyguard_current_wallpaper_type
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10049
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,D/SettingsProvider( 1019): name = keyguard_current_wallpaper_file_path
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10049
,D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,D/SettingsProvider( 1019): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10049
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5755): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/SViewCoverWidget( 1179): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167],
D/TEST    ( 1179): run!!!
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/GeometricMosaic_Renderer( 1179): setBackgroundBitmap
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5755): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,D/KeyguardEffectViewController( 1179): isPreloadedWallpaper=true
W/ContextImpl( 5755): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ResourcesManager( 5755): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5755): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Auth.Api.Credentials( 1933): [CredentialSyncAdapter] Unknown sync event.
,V/JNIHelp ( 5755): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/DriveInitializer( 1933): Background init thread started
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityThread( 5755): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 5755): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@30ed70da: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5755): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5755): GMSCore installation verified
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigStore( 5755): Config Database version: 1
,W/GAV2    ( 5773): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 5773): Created application version: 3.6.9 (30609)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/DriveInitializer( 1933): Awaiting to be initialized
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 1933): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/art     ( 1657): Explicit concurrent mark sweep GC freed 18552(1052KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 954us total 45.127ms
,D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  292): DCD OFF,
,D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1019): getStreamVolume 3 index 70
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/MediaRouter( 5755): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5755): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/NetworkMonitor( 5755): type=WIFI subType= reason=null isConnected=true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/DriveInitializer( 1933): Background init thread ended
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor( 5755): type=WIFI subType= reason=null isConnected=true
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5830): MountEmulatedStorage()
,I/libpersona( 5830): KNOX_SDCARD checking this for 10001
E/Zygote  ( 5830): v2,
I/libpersona( 5830): KNOX_SDCARD not a persona
I/SELinux ( 5830): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5830): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/art     ( 1019): Explicit concurrent mark sweep GC freed 63891(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 19.836ms total 217.940ms
,I/ActivityManager( 1019): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=5830 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 5830): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GHttpClientFactory( 5755): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/TimaKeyStoreProvider( 5830): TimaSignature is unavailable
,D/ActivityThread( 5830): Added TimaKeyStore provider
,I/BooksSync( 5773): Starting books sync for 61035162, extras: ade
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 5755): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5852): MountEmulatedStorage()
E/Zygote  ( 5852): v2
I/libpersona( 5852): KNOX_SDCARD checking this for 1000
I/libpersona( 5852): KNOX_SDCARD not a persona
,I/SELinux ( 5852): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1019): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=5852 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 5852): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Killing 5043:com.google.android.apps.docs/u0a87 (adj 15): empty #31
E/SELinux ( 5852): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5852): TimaSignature is unavailable
,D/ActivityThread( 5852): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1019): failed to open /acct/uid_10087/pid_5043/cgroup.procs: No such file or directory
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DIAGMON_AGENT( 5852): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/GLSUser ( 1657): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/login_manager
,I/GLSUser ( 1657): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/login_manager without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1657): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1657): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 5773): (284) automatic index on view_volumes(volume_id)
,E/Auth.Api.Credentials( 1933): [SyncManager] Error during the sync.
E/Auth.Api.Credentials( 1933): com.google.android.gms.auth.ad: BadAuthentication
E/Auth.Api.Credentials( 1933): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/Auth.Api.Credentials( 1933): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/Auth.Api.Credentials( 1933): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/Auth.Api.Credentials( 1933): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/Auth.Api.Credentials( 1933): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/Auth.Api.Credentials( 1933): 	at com.google.android.gms.common.server.s.b(SourceFile:59)
E/Auth.Api.Credentials( 1933): 	at com.google.android.gms.common.server.s.a(SourceFile:294)
E/Auth.Api.Credentials( 1933): 	at com.google.android.gms.common.server.s.a(SourceFile:201)
E/Auth.Api.Credentials( 1933): 	at com.google.android.gms.auth.b.a.a(SourceFile:316)
E/Auth.Api.Credentials( 1933): 	at com.google.android.gms.auth.api.credentials.be.a.b.b(SourceFile:285)
E/Auth.Api.Credentials( 1933): 	at com.google.android.gms.auth.api.credentials.sync.c.a(SourceFile:384)
E/Auth.Api.Credentials( 1933): 	at com.google.android.gms.auth.api.credentials.sync.b.a(SourceFile:114)
E/Auth.Api.Credentials( 1933): 	at com.google.android.gms.auth.api.credentials.sync.a.a(SourceFile:131)
E/Auth.Api.Credentials( 1933): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
E/Auth.Api.Credentials( 1933): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/BooksConfig( 5773): GmsCore Version = 7.8.99 (2134222-434)
,I/DIAGMON_AGENT( 5852): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/DIAGMON_AGENT( 5852): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 5852): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DIAGMON_AGENT( 5852): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 5852): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 5852): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/GLSUser ( 1657): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1657): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1657): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1657): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PicasaService( 4366): start picasa sync
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PicasaService( 4366): end picasa sync
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5112): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5112): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/WindowManager( 1019): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/DBG_POLICYDM( 5112): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,W/ResourcesManager( 1179): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1179): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 5112): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/KnoxNotification( 1179): ----- inflateViews : modified publicViewLocal -----
,D/KnoxNotification( 1179): ----- inflateViews : modified KnoxViewLocal -----
,E/Zygote  ( 5876): MountEmulatedStorage(),
E/Zygote  ( 5876): v2
I/ActivityManager( 1019): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=5876 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 5876): KNOX_SDCARD checking this for 10008
I/libpersona( 5876): KNOX_SDCARD not a persona
,I/SELinux ( 5876): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5876): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/PersonaManager( 1179): PersonaID is invalid or persona doesn't exists. : 0
,E/SELinux ( 5876): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1179): Icon Only
,I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,I/GLSUser ( 1657): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1657): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1657): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1657): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5876): TimaSignature is unavailable
,D/ActivityThread( 5876): Added TimaKeyStore provider
,E/BooksAccountManager( 5773): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/SQLiteLog( 1657): (10) POSIX Error : 11 SQLite Error : 3850
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/BooksSync( 5773): Soft error
E/BooksSync( 5773): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5773): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 5773): Sync error
E/BooksSync( 5773): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5773): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5773): Finished books sync
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 22291, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager( 1019): Killing 4998:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/ActivityManager( 1019): Killing 4667:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,I/ActivityManager( 1019): Killing 5093:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #32
,I/FOTA_Client( 5876): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 5876): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/ActivityManager( 1019): Killing 5127:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3431): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Dec 10 13:37:45 GMT+01:00 2015
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3431): KLMSAbstractReciever(): onReceive().END.
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
,I/KLMS-2.5.123: ( 3431): KLMSIntentService(): onCreate()
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 3431): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3431): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3431): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3431): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3431): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,E/Zygote  ( 5896): MountEmulatedStorage()
,E/Zygote  ( 5896): v2
I/libpersona( 5896): KNOX_SDCARD checking this for 10031
I/libpersona( 5896): KNOX_SDCARD not a persona
,I/SELinux ( 5896): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=5896 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
,I/SELinux ( 5896): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5896): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3431): StateImplV2(): networkChangeListener().START
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3431): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.5.123: ( 3431): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3431): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3431): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 5896): TimaSignature is unavailable
,D/ActivityThread( 5896): Added TimaKeyStore provider
,W/libprocessgroup( 1019): failed to open /acct/uid_10148/pid_5093/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10152/pid_5127/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10014/pid_4998/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10029/pid_4667/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5112): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5112): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5112): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5112): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,E/DBG_POLICYDM( 5112): [com.policydm.XDMBroadcastReceiver(240/xdmNotInitSetResume)] DM Not Init
,I/DBG_POLICYDM( 5112): [com.policydm.XDMApplication(246/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok
,I/SA      ( 5154): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5154): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 5154): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5112): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 5112): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 5154): [SLFUCHKMGR] constructor called
,I/DBG_POLICYDM( 5112): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,I/SA      ( 5154): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/DBG_POLICYDM( 5112): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,I/SA      ( 5154): [OR] == isSIMCardReady false ==
,I/DBG_POLICYDM( 5112): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,I/SA      ( 5154): [SCU] == networkStateCheck == true
,I/SA      ( 5154): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5154): isChinaCountryCode : false
I/SA      ( 5154): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5154): [OR] == networkStateCheck true ==
,I/SA      ( 5154): [OR] GetMyCountryZoneTask
,I/SA      ( 5154): [OR] onReceive END
,I/ActivityManager( 1019): Killing 4203:com.google.android.gms.wearable/u0a11 (adj 15): empty #31
,I/SA      ( 5154): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 1228): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/accuweather( 1576): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/SecContentProvider2( 1019): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1019): mCursor = null
,D/daemonapp( 1620): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,D/accuweather( 1576): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1576): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1576): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1576): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5154): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5154): [SSP] query invoked
,D/accuweather( 1576): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1576): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/SA      ( 5154): [TPMU] GetMccFromDB : null
I/SA      ( 5154): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5154): [TPM] isNoProxy(default) : true
,E/Zygote  ( 5923): MountEmulatedStorage(),
I/libpersona( 5923): KNOX_SDCARD checking this for 10121
E/Zygote  ( 5923): v2
I/libpersona( 5923): KNOX_SDCARD not a persona
I/SELinux ( 5923): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5923): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5923): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/ActivityManager( 1019): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=5923 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0,
E/File    ( 5154): fail readDirectory() errno=2,
,I/DBG_POLICYDM( 5112): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
D/TimaKeyStoreProvider( 5923): TimaSignature is unavailable
,D/ActivityThread( 5923): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5112): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,I/art     (  317): Explicit concurrent mark sweep GC freed 8706(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 622us total 28.648ms
,I/DBG_POLICYDM( 5112): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5112): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,W/ResourcesManager( 5923): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5923): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 5923): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup( 1019): failed to open /acct/uid_10011/pid_4203/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5112): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 5112): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 19.284ms
,I/DBG_POLICYDM( 5112): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 5112): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 5112): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 5112): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2015/12/10/14:45:39
,I/DBG_POLICYDM( 5112): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2015/12/10/13:37:45
,I/DBG_POLICYDM( 5112): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 5112): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 18.269ms
,I/DBG_POLICYDM( 5112): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 5112): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,D/QuickConnect( 5923): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 5923): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 5923): PeriphStartReceiver.onReceive - no need to start
,I/DBG_POLICYDM( 5112): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,I/DBG_POLICYDM( 5112): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 5604): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 5604): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5604): StateMachine : Current State = 1
,D/SecurityLogAgent( 5604): StateMachine : Changed Current State = 1
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,I/ActivityManager( 1019): Killing 5006:com.android.mms/u0a41 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10011
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/iu.SyncManager( 1933): SYNC; picasa accounts
,D/CountryDetector( 1019): No listener is left
,D/NetworkLogImpl( 1933): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1933): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.UploadsManager( 1933): num queued entries: 0
,I/iu.UploadsManager( 1933): num updated entries: 0
,W/libprocessgroup( 1019): failed to open /acct/uid_10041/pid_5006/cgroup.procs: No such file or directory
,I/iu.SyncManager( 1933): NEXT; no task
,D/ChimeraCfgMgr( 1933): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1933): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5948): MountEmulatedStorage(),
I/libpersona( 5948): KNOX_SDCARD checking this for 10032
E/Zygote  ( 5948): v2
I/libpersona( 5948): KNOX_SDCARD not a persona
I/SELinux ( 5948): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=5948 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5948): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
E/SELinux ( 5948): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5948): TimaSignature is unavailable
,D/ActivityThread( 5948): Added TimaKeyStore provider
,I/System.out( 5387): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5387): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5387): (HTTPLog)-Static: isShipBuild true
I/System.out( 5387): (HTTPLog)-Thread-937-945267646: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5387): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10102
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,I/GLSUser ( 1657): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1657): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1657): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1657): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 5387): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Kids    ( 1933): [AccountUtils] Account not ready
W/Kids    ( 1933): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1933): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1933): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1933): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1933): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1933): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1933): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1933): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1933): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1933): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1933): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1933): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/GCM     ( 1657): Connected
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1179): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,I/Babel   ( 5387): connection state changed from UNKNOWN to CONNECTED
,E/SPPClientService( 5948): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 5948): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 5948): PushLog.txt file is not deleted.
,D/SPPClientService( 5948): PushLog.txt file is not deleted.
D/SPPClientService( 5948): ============PushLog. stop!
,E/SPPClientService( 5948): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5948): [SystemStateMoniter] Current Time : 171102
,E/SPPClientService( 5948): [SystemStateMoniter] No Connect : false
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5969): MountEmulatedStorage(),
E/Zygote  ( 5969): v2
I/libpersona( 5969): KNOX_SDCARD checking this for 10110
I/libpersona( 5969): KNOX_SDCARD not a persona
,I/SELinux ( 5969): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5969 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 5969): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5969): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/GCM     ( 1657): Message class com.google.f.a.a.p
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/TimaKeyStoreProvider( 5969): TimaSignature is unavailable
,D/ActivityThread( 5969): Added TimaKeyStore provider
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5969): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 5969): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5969):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5969):   adb logcat -s GAv4
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5969): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5969): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 5969): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5969): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 5969): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5969): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager( 1019): Killing 5185:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,D/ConnectivityService( 1019): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1019): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1019): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1179): CM callback handler got msg 524295
,I/SurfaceFlinger(  258): id=13 Removed Uoast (8/9)
,I/SurfaceFlinger(  258): id=13 Removed Uoast (-2/9)
,D/PowerManagerService( 1019): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1019) eventTime = 171636
,D/PowerManagerService( 1019): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019 (0x0)
D/PowerManagerService( 1019): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1019, ws=WorkSource{10049}) (elapsedTime=3471)
,W/libprocessgroup( 1019): failed to open /acct/uid_10068/pid_5185/cgroup.procs: No such file or directory
,I/dhcpcd  ( 5714): wlan0: sending IPv6 Router Solicitation
,I/SA      ( 5154): [RC New] Execute method=[GET] start
,I/SA      ( 5154): [RC New] Security=[true]
,I/System.out( 5154): Thread-875(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5154): Thread-875(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5154): Thread-875(ApacheHTTPLog):isShipBuild true
,I/System.out( 5154): Thread-875(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5154): Thread-875(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10036
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1019): SIOP:: AP = 330
,I/WebViewFactory( 5969): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 5969): Time to load native libraries: 2 ms (timestamps 1835-1837)
,I/LibraryLoader( 5969): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5969): Binding Chromium to main looper Looper (main, tid 1) {3e4c23e9}
,I/LibraryLoader( 5969): Expected native library version number "",actual native library version number ""
,I/chromium( 5969): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5969): Initializing chromium process, singleProcess=true
,W/art     ( 5969): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5969): ApplicationContext is null in ApplicationStatus
,W/chromium( 5969): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5969): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5969): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5969): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5969): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5969): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5969): Local Branch: 
I/Adreno-EGL( 5969): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5969): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5969):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 5969): Requires BLUETOOTH permission
,I/NSApplication( 5969): Starting up...
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6025): MountEmulatedStorage(),
,E/Zygote  ( 6025): v2
,I/libpersona( 6025): KNOX_SDCARD checking this for 10077
I/libpersona( 6025): KNOX_SDCARD not a persona
,I/SELinux ( 6025): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6025 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6025): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Killing 5193:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,E/SELinux ( 6025): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6025): TimaSignature is unavailable
,D/ActivityThread( 6025): Added TimaKeyStore provider
,D/btif_config_util( 5523): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/libprocessgroup( 1019): failed to open /acct/uid_10042/pid_5193/cgroup.procs: No such file or directory
,E/SMD     (  292): DCD OFF
,D/WaitQueueForNetworkActivate( 5360): notifyNetworkActivated
,W/ContextImpl( 5360): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1019): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/SA      ( 5154): [RC New] [v2liruge] api execute + 715
,I/SA      ( 5154): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 5154): AsyncTask #1 calls detatch()
,I/SA      ( 5154): [ODM] saveOpenData( GEO_IP, PL ),
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 31083(1514KB) AllocSpace objects, 7(116KB) LOS objects, 33% free, 23MB/35MB, paused 2.486ms total 142.073ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5360): AutoUpdateManager:IDLE:execute,
,I/SA      ( 5154): [OCP] update openData : PL
,I/SA      ( 5154): [TPMU] getNetworkMcc : 
,I/splitIntent( 1019): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
,I/splitIntent( 1019): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,I/SA      ( 5154): [SCU] saveMccToPreferece Start
,I/SA      ( 5154): [SCU] RegionMCC : 260
I/SA      ( 5154): [SSP] query invoked
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/InitializeManagerStateMachine( 5360): execute::IDLE:EXECUTE
I/SA      ( 5154): [TPMU] GetMccFromDB : null
I/SA      ( 5154): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5154): [SCU] saveMccToPreferece End
,D/InitializeManagerStateMachine( 5360): exit::IDLE
D/InitializeManagerStateMachine( 5360): entry::NETWORK_CHECK
I/SA      ( 5154): [RC New] executeRequest [v2liruge] end. 940
I/SA      ( 5154): [RC New] Execute end
,I/SA      ( 5154): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5154): [OR] GetMyCountryZoneTask Success
,D/InitializeManagerStateMachine( 5360): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5360): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5360): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5360): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5360): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5360): entry::SUCCESS
D/hcjo    ( 5360): AutoUpdateManager:INITCHECK:onInitializeSuccess
,E/Zygote  ( 6048): MountEmulatedStorage()
,E/Zygote  ( 6048): v2
,I/libpersona( 6048): KNOX_SDCARD checking this for 10058
I/libpersona( 6048): KNOX_SDCARD not a persona
,I/SELinux ( 6048): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1019): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6048 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0,
I/SELinux ( 6048): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 6048): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 6062): MountEmulatedStorage(),
E/Zygote  ( 6062): v2
I/libpersona( 6062): KNOX_SDCARD checking this for 10131
I/libpersona( 6062): KNOX_SDCARD not a persona
,I/SELinux ( 6062): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6062 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 6062): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6062): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/FOTA_Client( 5876): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/hcjo    ( 5360): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 5360): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5360): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/daemonapp( 1620): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1620): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1620): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/FOTA_Client( 5876): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,D/TimaKeyStoreProvider( 6048): TimaSignature is unavailable
,D/InitializeManagerStateMachine( 5360): exit::SUCCESS
,D/InitializeManagerStateMachine( 5360): entry::IDLE
,D/ActivityThread( 6048): Added TimaKeyStore provider
,D/daemonapp( 1620): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/KLMS-2.5.123: ( 3431): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Dec 10 13:37:47 GMT+01:00 2015
,D/daemonapp( 1620): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/daemonapp( 1620): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,I/ActivityManager( 1019): Killing 5217:com.wsomacp/u0a23 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6062): TimaSignature is unavailable
,D/ActivityThread( 6062): Added TimaKeyStore provider
,D/comsamsunglog( 1620): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1620): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1620): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1620): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1620): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1620): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/KLMS-2.5.123: ( 3431): KLMSAbstractReciever(): onReceive().END.
,D/daemonapp( 1620): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,I/SA      ( 5154): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/daemonapp( 1620): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1620): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,W/ResourcesManager( 6062): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6062): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6062): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/daemonapp( 1620): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1620): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/KLMS-2.5.123: ( 3431): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3431): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3431): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/daemonapp( 1620): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/KLMS-2.5.123: ( 3431): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,I/KLMS-2.5.123: ( 3431): KLMSIntentService(): TIME_CHANGED
,I/KLMS-2.5.123: ( 3431): StateImplV2(): dateTimeChanged().START : Thu Dec 10 13:37:47 GMT+01:00 2015
,I/KLMS-2.5.123: ( 3431): StateImplV2(): dateTimeChanged().END
,I/KLMS-2.5.123: ( 3431): KLMSIntentService(): onDestroy()
,D/comdaemonstockapp( 1620): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1620): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,W/libprocessgroup( 1019): failed to open /acct/uid_10023/pid_5217/cgroup.procs: No such file or directory
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ExternalOEMControlProvider( 6048): onCreate
,D/accuweather( 1576): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/accuweather( 1576): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/ Time Manager ( 6048): Time Difference not stored. TIME_DIFFERENCE,
,I/ActivityManager( 1019): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=6084 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/Zygote  ( 6084): MountEmulatedStorage()
I/libpersona( 6084): KNOX_SDCARD checking this for 10041
E/Zygote  ( 6084): v2
I/libpersona( 6084): KNOX_SDCARD not a persona
,I/SELinux ( 6084): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 6084): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6084): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 6094): MountEmulatedStorage(),
I/libpersona( 6094): KNOX_SDCARD checking this for 10081
E/Zygote  ( 6094): v2
I/libpersona( 6094): KNOX_SDCARD not a persona
,I/SELinux ( 6094): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6094 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
I/SELinux ( 6094): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6094): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 1620): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/TimaKeyStoreProvider( 6084): TimaSignature is unavailable
,D/ActivityThread( 6084): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 6094): TimaSignature is unavailable
,D/ActivityThread( 6094): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ResourcesManager( 6084): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6084): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6084): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6084): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6084): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6116): MountEmulatedStorage()
E/Zygote  ( 6116): v2
,I/libpersona( 6116): KNOX_SDCARD checking this for 10037
I/libpersona( 6116): KNOX_SDCARD not a persona
,I/SELinux ( 6116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6116): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6116 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6094): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6094): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6094): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6094): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6094): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/SecurityLogAgent( 5604): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5604): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5604): StateMachine : Current State = 1
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6131 uid=10153 gids={50153, 9997} abi=armeabi-v7a
,E/Zygote  ( 6131): MountEmulatedStorage()
E/Zygote  ( 6131): v2
I/libpersona( 6131): KNOX_SDCARD checking this for 10153
I/SELinux ( 6131): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 6131): KNOX_SDCARD not a persona
,I/SELinux ( 6131): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6131): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6116): TimaSignature is unavailable
D/ActivityThread( 6116): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6131): TimaSignature is unavailable
,D/ActivityThread( 6131): Added TimaKeyStore provider
,W/ResourcesManager( 6131): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6116): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/Mms/MmsApp( 6084): [start]    onCreate() consume time = 0.0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6148): MountEmulatedStorage(),
E/Zygote  ( 6148): v2
I/libpersona( 6148): KNOX_SDCARD checking this for 1000
I/libpersona( 6148): KNOX_SDCARD not a persona
,I/SELinux ( 6148): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6148 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6148): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6148): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Killing 5238:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31
,I/ActivityManager( 1019): Killing 5261:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6148): TimaSignature is unavailable
,D/ActivityThread( 6148): Added TimaKeyStore provider
,D/TimeService( 6148): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449751067904
D/        ( 6148): TimeServiceNative: User Time to be set is 1449751067904
D/QC-time-services( 6148): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6148): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6148): Lib:time_genoff_operation: pargs->ts_val = 1449751067904
,D/QC-time-services(  333): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 6148): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  333): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449751067904
D/QC-time-services(  333): Daemon:genoff_opr: Base = 2, val = 1449751067904, operation = 0
D/QC-time-services(  333): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/6/70 6:23:19
D/QC-time-services(  333): Daemon:Value read from RTC seconds = 13501399000,
D/QC-time-services(  333): Daemon:new time 1449751067904 
D/QC-time-services(  333): Daemon: delta 1436249668904 genoff 1436249668904 
,D/QC-time-services(  333): Daemon:genoff_persistent_update: Writing genoff = 1436249668904 to memory
D/QC-time-services(  333): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  333): Daemon:time_persistent_memory_opr:Genoff write operation ,
,D/QC-time-services(  333): Updating the TOD offset
D/QC-time-services(  333): Daemon:genoff_persistent_update: Writing genoff = 1436249668904 to memory
D/QC-time-services(  333): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  333): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  333): Daemon:Update to modem bit set
D/QC-time-services(  333): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  333): Daemon: Base = 2, Value being sent to MODEM = 1120284868904
,E/QC-time-services(  333): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  333): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services( 6148): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager( 1019): Killing 5277:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #31
,I/CalendarProvider2( 6116): CalendarProvider2.onCreate() called
,W/art     ( 6084): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 143.340ms
,D/SettingsProvider( 1019): name = next_alarm_formatted
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10081
,D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1019): ret = -1
,W/libprocessgroup( 1019): failed to open /acct/uid_10048/pid_5238/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5261/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5277/cgroup.procs: No such file or directory
,D/Mms/ArtClassLoader( 6084): init before art
,D/Mms/TelephonyPermission( 6084): start operation mode monitor
,W/ResourcesManager( 6084): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission( 6084): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 6084): isDefault true
,W/art     ( 6094): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 119.322ms
D/Mms/MmsApp( 6084): onCreate() com.android.mms
,D/Mms/MmsApp( 6084): [start]    initCountryIso consume time = 328.414688
,D/CountryDetector( 1019): The first listener is added
,D/Mms/MmsApp( 6084): [end]    initCountryIso consume time = 8.550937
,D/Mms/MmsConfig( 6084): [start]    MmsConfig.init() consume time = 0.455573
,D/Mms/MmsConfig( 6084): before partial update
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6168): MountEmulatedStorage(),
,E/Zygote  ( 6168): v2
I/libpersona( 6168): KNOX_SDCARD checking this for 10090
,I/libpersona( 6168): KNOX_SDCARD not a persona
,I/SELinux ( 6168): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6168 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 5300:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,I/SELinux ( 6168): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6168): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6168): TimaSignature is unavailable
,D/ActivityThread( 6168): Added TimaKeyStore provider
I/art     (  317): Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 26.801ms
,D/Mms/MmsConfig( 6084): Load Resize quality : 80
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 866us total 17.805ms
,D/EasySignUpManager_1.0.1( 6084): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 6084): isAuth is false
,D/Mms/MmsConfig( 6084): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 750us total 20.402ms
,D/TP/MmsSmsProvider( 1452): query,matched:2117, calling pid = 6084
,D/TP/MmsSmsProvider( 1452): match 2117:Elapsed time : 2.735 ms
,D/EasySignUpManager_1.0.1( 6084): isAuth is false
,D/EasySignUpManager_1.0.1( 6084): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 6084): mps_code.dat does not exist
E/CscParser( 6084): customer_path =/system/csc/customer.xml
E/CscParser( 6084): fileName + /system/csc/customer.xml
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/CscParser( 6084): mps_code.dat does not exist
E/CscParser( 6084): customer_path =/system/csc/customer.xml
E/CscParser( 6084): fileName + /system/csc/customer.xml
,D/elm:15121( 6168): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15121( 6168): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6168): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6168): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
W/libprocessgroup( 1019): failed to open /acct/uid_10098/pid_5300/cgroup.procs: No such file or directory
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/elm:15121( 6168): ElmAgentService : onCreate()
D/CscParser( 6084): getInstance fileName =/system/csc/customer.xml
,D/elm:15121( 6168): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:15121( 6168): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:15121( 6168): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5075): mConnectivityHandler : connected
,E/Zygote  ( 6190): MountEmulatedStorage()
I/libpersona( 6190): KNOX_SDCARD checking this for 10130
E/Zygote  ( 6190): v2
I/libpersona( 6190): KNOX_SDCARD not a persona
,I/SELinux ( 6190): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6190): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6190): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6190 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,D/Mms/MmsConfig( 6084):  enable multiwindow = false
,D/elm:15121( 6168): ModuleBase.ModifySetAlarm(),
D/elm:15121( 6168): MDMBridge.getInstance()
D/elm:15121( 6168): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 6168): ElmAgentService : onDestroy().
,I/ActivityManager( 1019): Killing 5344:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #31
,W/PCWCLIENTTRACE_AccountUtil( 5075): [hasSamungAccount] - No Samsung Account
,E/Mms/MessageUtils( 6084): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 6084): updateCountryIso : update country iso info 
,D/TimaKeyStoreProvider( 6190): TimaSignature is unavailable
,D/ActivityThread( 6190): Added TimaKeyStore provider
,D/Mms/MmsConfig( 6084): [end]    init() consume time = 235.670833
,D/Mms/Contact( 6084): [start]    init() consume time = 0.619167
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5075): [GetString-S]
,D/Mms/Contact( 6084): [end]    init consume time = 21.714115
,D/TP/MmsSmsProvider( 1452): query,matched:13, calling pid = 6084
,W/ResourcesManager( 6190): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6190): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/TP/MmsSmsProvider( 1452): match 13:Elapsed time : 3.384 ms
,I/ReactiveServiceManager( 5075): Supported : 1
,D/Mms/DraftCache( 6084): [start]    rebuildCache consume time = 16.3925
,D/Mms/MethodReflector( 6084): getSubId is called
D/Mms/TelephonyUtils( 6084): getLongSubId from simSlot 0, return Value = -1
,D/TP/MmsSmsProvider( 1452): query,matched:12, calling pid = 6084
,D/TP/MmsSmsProvider( 1452): match 12:Elapsed time : 1.877 ms
,D/Mms/MethodReflector( 6084): getTelephonyProperty is called
D/Mms/DownloadManager( 6084): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6084): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6084): auto download without roaming -> true
D/Mms/DownloadManager( 6084): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/MethodReflector( 6084): getSubId is called
,D/QSEECOMAPI: ( 1019): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1019): App is not loaded in QSEE
D/Mms/MethodReflector( 6084): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 6084): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 6084): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 6084): getTelephonyProperty is called
D/Mms/DownloadManager( 6084): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 6084): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 6084): auto download without roaming -> true
D/Mms/DownloadManager( 6084): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 6084): auto download during roaming secondary -> false
D/Mms/DownloadManager( 6084): mAutoDownload ------> true
,D/ComposerPerformance( 6084): 1449751068430 ms / [DONE] Composer constructor
,D/Mms/DraftCache( 6084): [end]    rebuildCache consume time = 23.264948
,E/CII     ( 6084): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 6084): ReservationManager()
,I/Mms/ReservationManager( 6084): resetAfterConnected()
,I/ActivityManager( 1019): Killing 4964:com.android.defcontainer/u0a3 (adj 15): empty #31
,D/TP/MmsSmsProvider( 1452): query,matched:7, calling pid = 6084
,D/TP/MmsSmsProvider( 1452): match 7:Elapsed time : 2.685 ms
,I/Mms/ReservationManager( 6084): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/Conversation( 6084): [start]    init() consume time = 27.899583
,D/Mms/ArtClassLoader( 6084): init [DONE] art
,D/QSEECOMAPI: ( 1019): Loaded image: APP id = 9
,D/Mms/MmsApp( 6084): [end]    onCreate() consume time = 2.441823
D/TP/MmsSmsProvider( 1452): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1452): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1452): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1452): sUpgradeVersion = 0, db.getVersion() = 81
,W/libprocessgroup( 1019): failed to open /acct/uid_10052/pid_5344/cgroup.procs: No such file or directory
,I/ActivityManager( 1019): Killing 4742:com.android.vending/u0a26 (adj 15): empty #31
,D/TP/MmsSmsProvider( 1452): delete threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1452): need read changed broadcast:false
,D/Mms/DownloadManager( 6084): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/QSEECOMAPI: ( 1019): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1019): QSEECom_shutdown_app, app_id = 9
D/Mms/DownloadManager( 6084): roaming ------> false, mSimSlot = 0
E/terrier ( 1019): handleString: Failed to handle string(-4)
E/terrier ( 1019): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,I/splitIntent( 1019): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
D/Mms/Conversation( 6084): [end]    init consume time = 14.206667
D/Mms/MessagingNotification( 6084): [start]    init() consume time = 0.07526
,D/Mms/MethodReflector( 6084): getSubId is called
D/Mms/TelephonyUtils( 6084): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 6084): getTelephonyProperty is called
,I/ActivityManager( 1019): Killing 5667:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #31
D/Mms/DownloadManager( 6084): roaming -> false (slotId = 0)
,D/Mms/DownloadManager( 6084): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6084): auto download without roaming -> true
D/Mms/DownloadManager( 6084): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/DownloadManager( 6084): mAutoDownload ------> true
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5075): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5075): [GetString-E]
,D/Mms/MessagingNotification( 6084): [end]    init consume time = 6.95776
,I/PCWCLIENTTRACE_PushUtil( 5075): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5075): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5075): getPushTypeList : [SPP, GCM]
D/TP/MmsSmsProvider( 1452): query,matched:0, calling pid = 6084
V/TP/MmsSmsProvider( 1452): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1452): match 0:Elapsed time : 0.991 ms
E/PCWCLIENTTRACE_PCWHandler( 5075): [ensureRegistration] - No Samsung account
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/Mms/SpamFilter( 6084): [start]    SpamFilter fill() begin consume time = 17.209844
,D/TP/MmsSmsProvider( 1452): query,matched:400, calling pid = 6084
,D/Mms/SpamFilter( 6084): [end]    SpamFilter fill() finished consume time = 5.152865
,D/Mms/Synchronizer( 6084): [start]    doSync consume time = 1.369166
,D/TP/MmsSmsProvider( 1452): update, matched:300, calling pid = 6084
V/TP/MmsSmsProvider( 1452): syncDBData start
,V/TP/MmsSmsProvider( 1452): syncDBData sms end
,V/TP/MmsSmsProvider( 1452): syncDBData mms end
,V/TP/MmsSmsProvider( 1452): syncDBData end
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5112): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,E/Zygote  ( 6214): MountEmulatedStorage()
I/libpersona( 6214): KNOX_SDCARD checking this for 10068
E/Zygote  ( 6214): v2
I/libpersona( 6214): KNOX_SDCARD not a persona
I/SELinux ( 6214): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6214 uid=10068 gids={50068, 9997} abi=armeabi-v7a
I/SELinux ( 6214): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6214): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/Mms/Synchronizer( 6084): [end]    doSync consume time = 40.583177
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5112): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
D/TimaKeyStoreProvider( 6214): TimaSignature is unavailable
,D/ActivityThread( 6214): Added TimaKeyStore provider
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5112): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,W/libprocessgroup( 1019): failed to open /acct/uid_10003/pid_4964/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10026/pid_4742/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10064/pid_5667/cgroup.procs: No such file or directory
,E/DBG_POLICYDM( 5112): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/BadgeProvider( 6214): onCreate
D/BadgeProvider( 6214): DatabaseHelper
,I/DBG_POLICYDM( 5112): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5112): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Mms/MessagingNotification( 6084): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1452): query,matched:26, calling pid = 6084
,D/TP/SmsProvider( 1452): match 26:Elapsed time : 1.730 ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsSmsProvider( 1452): query,matched:6, calling pid = 6084
,D/TP/MmsSmsProvider( 1452): match 6:Elapsed time : 3.441 ms
,I/ActivityManager( 1019): Killing 5685:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6230): MountEmulatedStorage()
E/Zygote  ( 6230): v2
I/libpersona( 6230): KNOX_SDCARD checking this for 10023
I/libpersona( 6230): KNOX_SDCARD not a persona
,I/SELinux ( 6230): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6230): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6230): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6230 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6230): TimaSignature is unavailable
,D/ActivityThread( 6230): Added TimaKeyStore provider
,W/libprocessgroup( 1019): failed to open /acct/uid_10065/pid_5685/cgroup.procs: No such file or directory
,D/PerfProfileCollectorService( 1933): User is not opt-in to Usage & Diagnostics.
,D/PerfProfileCollectorService( 1933): removeStateFiles() called
,D/PerfProfileCollectorService( 1933): User is not opt-in to Usage & Diagnostics.
,D/Batterystats( 1933): User is not opted-in to Usage & Diagnostics.
,I/ActivityManager( 1019): Killing 5566:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,I/OMACP   ( 6230): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp( 6084): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/OMACP   ( 6230): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 6230): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 6230): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 6230): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 6230): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 6230): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 6230): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 6230): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 6230): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false,
,I/OMACP   ( 6230): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 6230): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 6230): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 6230): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,W/libprocessgroup( 1019): failed to open /acct/uid_10055/pid_5566/cgroup.procs: No such file or directory
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 13899(643KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.523ms total 144.240ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/GAV2    ( 5773): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6254 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,E/Zygote  ( 6254): MountEmulatedStorage(),
E/Zygote  ( 6254): v2
I/libpersona( 6254): KNOX_SDCARD checking this for 10011
I/libpersona( 6254): KNOX_SDCARD not a persona
,I/SELinux ( 6254): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6254): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
E/SELinux ( 6254): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/TimaKeyStoreProvider( 6254): TimaSignature is unavailable
,D/ActivityThread( 6254): Added TimaKeyStore provider
,I/MusicLeanback( 5755): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 5755): Stop autocaching.
,W/ResourcesManager( 6254): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6254): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6254): VM with version 2.1.0 has multidex support
,I/MultiDex( 6254): install
I/MultiDex( 6254): VM has multidex support, MultiDex support library is disabled.
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/JNIHelp ( 6254): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/CalendarProvider2( 6116): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityThread( 6254): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6254): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a8dc04: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6254): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1019): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,D/GCM     ( 1657): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/splitIntent( 1019): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1019): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1657): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1933): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 6254): callingUid 10011, callindPid: 6254
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1667): [186] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1933): Restart initialization of location
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/GmsUtils( 5755): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5755): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager( 1019): Killing 5075:com.sec.pcw.device/1000 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5075/cgroup.procs: No such file or directory
,E/SMD     (  292): DCD OFF
,I/dhcpcd  ( 5714): wlan0: sending IPv6 Router Solicitation
,I/Mms/MmsApp( 6084):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 6084): [start]    fillCache consume time = 1916.093958
D/Mms/ComposeMessageFragment( 6084): fillCache, easy = false
,D/AbsListView( 6084): Get MotionRecognitionManager
,D/MotionRecognitionService( 1019):  ssp status : false
,D/Mms/ComposeMessageFragment( 6084): [end]    fillCache consume time = 75.311094
,D/Mms/BubbleViewCache( 6084): fillCache bubble = 1
,I/jxcore-log( 5473): Test app app.js loaded
I/jxcore-log( 5473): 
,I/Choreographer( 5473): Skipped 716 frames!  The application may be doing too much work on its main thread.
,I/chromium( 5473): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1399): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1399): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5523): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5523): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1179): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6284): MountEmulatedStorage()
I/libpersona( 6284): KNOX_SDCARD checking this for 10026
E/Zygote  ( 6284): v2
I/libpersona( 6284): KNOX_SDCARD not a persona
,I/ActivityManager( 1019): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentFiltersService: pid=6284 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6284): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6284): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6284): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6284): TimaSignature is unavailable
,D/ActivityThread( 6284): Added TimaKeyStore provider
,D/Finsky  ( 6284): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6284): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6318): MountEmulatedStorage()
,E/Zygote  ( 6318): v2
I/libpersona( 6318): KNOX_SDCARD checking this for 10011
I/libpersona( 6318): KNOX_SDCARD not a persona
,I/SELinux ( 6318): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6318 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 6318): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6318): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/Settings( 6284): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6284): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TimaKeyStoreProvider( 6318): TimaSignature is unavailable
,D/ActivityThread( 6318): Added TimaKeyStore provider
,W/ResourcesManager( 6318): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6318): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6318): VM with version 2.1.0 has multidex support
I/MultiDex( 6318): install
I/MultiDex( 6318): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager( 1019): Killing 5830:com.sec.android.cloudagent/u0a1 (adj 15): empty #31
,I/dhcpcd  ( 5714): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 5714): wlan0: no IPv6 Routers available
,V/JNIHelp ( 6318): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager( 1019): Killing 5852:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/Finsky  ( 6284): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6284): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6284): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 6284): [1074] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6284): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityThread( 6318): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6318): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a8dc04: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6318): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1019): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1019): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1019): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1657): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1657): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/libprocessgroup( 1019): failed to open /acct/uid_10001/pid_5830/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5852/cgroup.procs: No such file or directory
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1933): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1657): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1657): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1657): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1657): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 6254): callingUid 10011, callindPid: 6254
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1667): [187] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6284): [1074] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1933): Restart initialization of location
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1657): Explicit concurrent mark sweep GC freed 26602(1528KB) AllocSpace objects, 8(153KB) LOS objects, 40% free, 7MB/12MB, paused 1.016ms total 55.920ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/Finsky  ( 6284): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,V/AlarmManager( 1019): waitForAlarm result :4
,D/Finsky  ( 6284): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1657): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1657): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1657): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1657): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6284): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1657): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1657): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1657): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1657): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1657): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1657): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1657): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1657): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6284): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1657): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1657): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1657): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1657): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6284): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6284): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6284): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6284): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,D/DeviceConnectionService( 1667): client connected with version: 7571000
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 330
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5360): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5360): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5360): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5360): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5360): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5360): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5360): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5360): entry::IDLE
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ActivityManager( 1019): Killing 4366:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,W/libprocessgroup( 1019): failed to open /acct/uid_10039/pid_4366/cgroup.procs: No such file or directory
,V/AlarmManager( 1019): waitForAlarm result :8
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1399): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1399): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/HeadsetService( 5523): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5523): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,I/PowerManagerService( 1019): [PWL] Off : 140s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 300
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 6,
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1179): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1657): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1657): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1657): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1657): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 28060(1437KB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 23MB/35MB, paused 2.485ms total 136.844ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6284): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6284): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6284): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,I/Atfwd_Sendcmd(  331): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  331): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 290,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1399): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1399): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5523): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5523): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/Watchdog( 1019): !@Sync 7,
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 1
,V/AlarmManager( 1019): waitForAlarm result :4
,I/BooksSync( 5773): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 5773): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1657): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1657): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1657): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1657): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1657): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1657): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1657): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1657): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5773): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5773): Soft error
E/BooksSync( 5773): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5773): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 5773): Sync error
E/BooksSync( 5773): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5773): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5773): Finished books sync
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 200600, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  292): DCD OFF
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,I/PowerManagerService( 1019): [PWL] Off : 180s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1399): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1399): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5523): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5523): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1399): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1399): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 5523): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5523): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1179): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 8
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1179): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1019): [PWL] Off : 225s ago
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 9
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,I/BooksSync( 5773): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 5773): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1657): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1657): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1657): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1657): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1657): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1657): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1657): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1657): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/BooksAccountManager( 5773): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5773): Soft error
E/BooksSync( 5773): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5773): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 5773): Sync error
E/BooksSync( 5773): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5773): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5773): Finished books sync
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 289994, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1019): initializing...
,I/TLC_TIMA_PKM_initialize( 1019): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1019): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1019): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1019): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1019): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1019): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1019): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1019): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: ( 1019): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1019): Loaded image: APP id = 10
,I/TZ: qc_tlc_communication( 1019): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1019): Trustlet response is completed
,E/SMD     (  292): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1399): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1399): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5523): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5523): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1179): level :100 plugged : 2
,E/Watchdog( 1019): !@Sync 10
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1179): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1019): SIOP:: AP = 270,
,E/SMD     (  292): DCD OFF
,I/Atfwd_Sendcmd(  331): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  331): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 275s ago
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1399): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1399): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 5523): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5523): Disconnected process message: 10
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,E/SMD     (  292): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 270,
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  292): DCD OFF

```
