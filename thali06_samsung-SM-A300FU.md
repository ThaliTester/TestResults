#### Test 55742142a5c2fdb_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
I/PowerManagerService( 1019): [PWL] Off : 75s ago
,--------- beginning of main
D/AndroidRuntime( 6048): 
D/AndroidRuntime( 6048): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6048): CheckJNI is OFF
D/AndroidRuntime( 6048): readGMSProperty: start
D/AndroidRuntime( 6048): readGMSProperty: already setted!!
D/AndroidRuntime( 6048): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6048): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6048): readGMSProperty: end
D/AndroidRuntime( 6048): addProductProperty: start
E/AffinityControl( 6048): AffinityControl: registerfunction enter
D/AndroidRuntime( 6048): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1019): mDVFSHelper.acquire()
D/FocusedStackFrame( 1019): Set to : 0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1019): *FMB* installDecor flags : 25362712
E/Zygote  ( 6060): MountEmulatedStorage()
E/Zygote  ( 6060): v2
I/libpersona( 6060): KNOX_SDCARD checking this for 10338
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6060 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 1478
I/libpersona( 6060): KNOX_SDCARD not a persona
I/SELinux ( 6060): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/AndroidRuntime( 6048): Shutting down VM
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 6060): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6060): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6060): TimaSignature is unavailable
D/ActivityThread( 6060): Added TimaKeyStore provider
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1019): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1478): updateVisibility : ActivityRecord{f9c2d82 token=android.os.BinderProxy@13efb94f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1478): onTrimMemory. Level: 20
I/WebViewFactory( 6060): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6060): Time to load native libraries: 1 ms (timestamps 4041-4042)
I/LibraryLoader( 6060): Expected native library version number "",actual native library version number ""
W/art     ( 6048): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6060): Binding Chromium to main looper Looper (main, tid 1) {11b1e958}
,I/LibraryLoader( 6060): Expected native library version number "",actual native library version number ""
,I/chromium( 6060): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6060): Initializing chromium process, singleProcess=true
,W/art     ( 6060): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6060): ApplicationContext is null in ApplicationStatus
,W/chromium( 6060): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6060): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6060): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6060): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6060): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6060): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6060): Local Branch: 
I/Adreno-EGL( 6060): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6060): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6060):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6060): Attempt to remove local handle scope entry from IRT, ignoring
,E/SMD     (  289): DCD OFF
,W/AwContents( 6060): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6060): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6060): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6060): CordovaWebView is running on device made by: samsung
,W/art     ( 6060): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6060): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1019): Activity pause timeout for ActivityRecord{306a45e3 u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 6060): Render dirty regions requested: true
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
W/chromium( 6060): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6060): updateVisibility : ActivityRecord{24d3ef5d token=android.os.BinderProxy@564a007 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 6060): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6060): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1019): Focus entered window: 6060
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6060): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6060): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6060): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6060): Enabling debug mode 0
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1019): Displayed Component not be shown by security: +620ms (total +38s207ms)
W/ActivityManager( 1019): mDVFSHelper.release()
I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{306a45e3 u0 com.test.thalitest/.MainActivity t20} time:154510
,I/SurfaceFlinger(  258): id=12 Removed uhalitest (7/9)
,I/SurfaceFlinger(  258): id=12 Removed uhalitest (-2/9)
,W/IInputConnectionWrapper( 6060): showStatusIcon on inactive InputConnection,
I/Timeline( 6060): Timeline: Activity_idle id: android.os.BinderProxy@564a007 time:154521,
,I/SamsungIME( 1783): getCurrentCandidateView
,D/SamsungIME( 1783): Dismiss ExpandCandiate
,I/SamsungIME( 1783): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1783): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1783): KeybaordView init() : load resources
,W/BindingManager( 6060): Cannot call determinedVisibility() - never saw a connection for the pid: 6060
,I/SamsungIME( 1783): getCurrentKeyboard
,I/SamsungIME( 1783): getTextKeyboard
,D/SamsungIME( 1783): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 6060): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6060): JniHelper::setJavaVM(0xb7e7b448), pthread_self() = -1203944232
,D/JX-Cordova( 6060): jxcore cordova android initializing
,V/AlarmManager( 1019): waitForAlarm result :4
I/BooksSync( 5981): Starting books sync for 61035162, extras: ade
I/BooksConfig( 5981): GmsCore Version = 7.8.99 (2134222-434)
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/jxcore-log( 6060): Initializing JXcore engine
W/jxcore-log( 6060): JXcore engine is ready
I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/jxcore-log( 6060): Starting JXcore engine
V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
E/audit   ( 1833): type=1400 msg=audit(1452601002.150:205): avc:  denied  { ioctl } for  pid=6060 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1833):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1833): type=1300 msg=audit(1452601002.150:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=beaf9d58 items=0 ppid=306 ppcomm=main pid=6060 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1833): type=1320 msg=audit(1452601002.150:205): 
I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
E/BooksAccountManager( 5981): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
E/BooksSync( 5981): Soft error
E/BooksSync( 5981): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5981): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 5981): Sync error
E/BooksSync( 5981): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5981): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5981): Finished books sync
D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 156165, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
W/jxcore-log( 6060): Platform android
W/jxcore-log( 6060): 
W/jxcore-log( 6060): Process ARCH arm
W/jxcore-log( 6060): 
D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2654): Disconnected process message: 10
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/jxcore-log( 6060): JXcore Cordova bridge is ready!
I/jxcore-log( 6060): 
,W/jxcore-log( 6060): JXcore engine is started
,I/chromium( 6060): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/jxcore-log( 6060): Toggling radios to true,
I/jxcore-log( 6060): 
,D/BluetoothAdapter( 6060): enable(),
,D/BluetoothAdapter( 6060): enable(): BT is already enabled..!,
,D/SecContentProvider( 1019): uri = 18 selection = isWifiEnabled,
D/SecContentProvider2( 1019): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1019): mCursor = null
,D/WifiService( 1019): setWifiEnabled: true pid=6060, uid=10338
,W/ActivityManager( 1019): Permission Denial: getCurrentUser() from pid=6060, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1019): Failed getting userId using ActivityManagerNative
W/WifiService( 1019): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6060, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1019): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1019): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1019): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1019): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1019): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1019): name = wifi_on
,I/WifiService( 1019): disconnect: pid=6060, uid=10338
,I/wpa_supplicant( 1398): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6060): Radios toggled
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): Received device characteristics:
I/jxcore-log( 6060): Bluetooth address: 08:EC:A9:50:75:41
I/jxcore-log( 6060): Bluetooth name: A3-1
I/jxcore-log( 6060): Device name: samsung-SM-A300FU
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): Perf Test app loaded loaded
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): check test folder
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): found test : ./testFindPeers.js
I/jxcore-log( 6060): 
,I/wpa_supplicant( 1398): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1,
I/wpa_supplicant( 1398): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1398): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 1398): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1398): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 1019): WifiStateMachine: Leaving Connected state
D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1398): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1398): wlan0: Setting scan request: 0 sec 0 usec
E/wpa_supplicant( 1398): Cmd 35605 not handled
I/wpa_supplicant( 1398): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1398): wlan0: State: DISCONNECTED -> SCANNING
,I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1398): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1398): First Scan Start
D/Tethering( 1019): InitialState.processMessage what=4
I/wpa_supplicant( 1398): Scan requested (ret=0) - scan timeout 30 seconds
I/jxcore-log( 6060): found test : ./testSendData.js
I/jxcore-log( 6060): 
D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false
,E/WifiConfigStore( 1019): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/Tethering( 1019): No numeric data
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
,I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): clearTetheredNotification()
D/Tethering( 1019): interfaceStatusChanged wlan0, false
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
,D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false
,V/NetworkStats( 1019): performPollLocked() took 5ms
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,E/WifiNative-wlan0( 1019): do suspend true
,D/WifiP2pService( 1019): InactiveState{ what=143375 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/CommandListener(  279): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/ConnectivityService( 1019): updateNetworkInfo()
D/ConnectivityService( 1019): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1019): updateNetworkInfo()
D/ConnectivityService( 1019): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine( 1019): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1398): wlan0: Setting scan request: 0 sec 0 usec
,V/NativeCrypto( 1650): Read error: ssl=0xb83a9270: I/O error during system call, Connection timed out
,I/WifiTrafficPoller( 1019): evaluateTrafficStatsPolling
E/WifiNative-wlan0( 1019): do suspend true
,D/WifiP2pService( 1019): InactiveState{ what=143375 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=143375 }
V/NativeCrypto( 1650): SSL shutdown failed: ssl=0xb83a9270: I/O error during system call, Broken pipe
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7d417c8
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1210836856)
,D/ConnectivityService( 1019): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1019): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1019): Tagging socket 344 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1019, getuid(): 1000
,D/CommandListener(  279): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/qtaguid ( 1019): Untagging socket 344
,I/System.out( 1019): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/WifiTrafficPoller( 1019): evaluateTrafficStatsPolling
I/Hs20UtilService( 2065): Starting #8
,I/Hs20UtilService( 2065): Message received 5007
,D/WifiNetworkAgent( 1019): NetworkAgent: NetworkAgent channel lost
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled,
D/SecContentProvider2( 1019): mCursor = null
,D/NearbySettings( 1361): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1361): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1361): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1361): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1361): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1361): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1361): MountReceiver.mPrefHandler - 7002
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1210836856) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
,I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7d417c8
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 2065): Starting #9
,I/Hs20UtilService( 2065): Message received 5007
,D/NearbySettings( 1361): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1361): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1361): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1361): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1361): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1361): MountReceiver.onReceive - Set preference state off
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
,D/ConnectivityService( 1019): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1019): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/WIFI    ( 1019): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1019): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI_P2P( 1019): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1019): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/CSLegacyTypeTracker( 1019): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Validated
D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
V/NearbySettings( 1361): MountReceiver.mPrefHandler - 7002
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 1446): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1446): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EntConnectivity( 1019): Not allowed due to - mEnabled false - primarySimSlot false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6119): MountEmulatedStorage()
E/Zygote  ( 6119): v2
I/libpersona( 6119): KNOX_SDCARD checking this for 10102
,I/libpersona( 6119): KNOX_SDCARD not a persona
,I/SELinux ( 6119): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6119): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6119 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/SELinux ( 6119): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
D/Tethering( 1019): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1019): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1019): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): doQuit - quitNow()
D/EntConnectivity( 1019): Not allowed due to - mEnabled false - primarySimSlot false
V/NetworkStats( 1019): updateIfacesLocked()
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): performPollLocked() took 7ms
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
I/chromium( 6060): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/TimaKeyStoreProvider( 6119): TimaSignature is unavailable
,D/ActivityThread( 6119): Added TimaKeyStore provider
,W/ResourcesManager( 6119): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1446): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1446): FileWriteThread : threadType = 3
,D/PhoneApp( 1446): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1446): FileWriteThread : threadType = 3
,D/PhoneApp( 1446): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1446): FileWriteThread : threadType = 3
D/PhoneApp( 1446): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1446): FileWriteThread : threadType = 3
,D/PhoneApp( 1446): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1446): FileWriteThread : threadType = 3
,D/PhoneApp( 1446): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1446): FileWriteThread : threadType = 3
,D/PhoneApp( 1446): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1446): FileWriteThread : threadType = 3
,D/PhoneApp( 1446): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1446): FileWriteThread : threadType = 3
,D/PhoneApp( 1446): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1446): FileWriteThread : threadType = 3
,D/PhoneApp( 1446): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1446): FileWriteThread : threadType = 3,
D/PhoneApp( 1446): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1446): FileWriteThread : threadType = 3
D/PhoneApp( 1446): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1446): FileWriteThread : threadType = 3
,D/PhoneApp( 1446): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1446): FileWriteThread : threadType = 3
D/PhoneApp( 1446): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1446): FileWriteThread : threadType = 3
D/PhoneApp( 1446): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1446): FileWriteThread : threadType = 3
,I/Babel_SMS( 6119): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6119): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6119): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,I/Babel_SMS( 6119): MmsConfig.loadFromDatabase
E/Babel_SMS( 6119): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6119): MmsConfig.loadFromResources
E/Babel_SMS( 6119): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6119): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  284): getCameraInfo: X
,W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  284): getCameraInfo: X
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk,
,W/Settings( 6119): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6119): startup - clean
,I/Babel   ( 6119): deleted: false for 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6119): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/AudioCapabilities( 6119): Unsupported mime audio/evrc
,W/AudioCapabilities( 6119): Unsupported mime audio/qcelp,
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/AudioCapabilities( 6119): Unsupported mime audio/mpeg-L1
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/AudioCapabilities( 6119): Unsupported mime audio/mpeg-L2
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6119): Unsupported mime audio/x-ms-wma
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6119): Unsupported mime audio/x-ima
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6119): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6119): Unsupported mime audio/evrc
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6119): Unsupported mime video/wvc1
,W/VideoCapabilities( 6119): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6119): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6119): Unsupported mime video/wvc1
,W/VideoCapabilities( 6119): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6119): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6119): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6119): Unsupported mime video/mp43
,W/VideoCapabilities( 6119): Unsupported mime video/sorenson
,W/VideoCapabilities( 6119): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6119): Unsupported profile 4 for video/mp4v-es
,D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1019): updateDataUsageMap
,W/VideoCapabilities( 6119): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6119): Unrecognized profile 2130706433 for video/avc
,D/GpsLocationProvider( 1019): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/VideoCapabilities( 6119): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6119): Unrecognized profile 2130706433 for video/avc
,I/PCWCLIENTTRACE_PushUtil( 5638): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5638): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5638): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5638): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1019): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1019): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1019): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/vclib   ( 6119): onServiceConnected
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/Babel   ( 6119): Attempted to change video mute state without an active call.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5638): noConnectivity : true
,I/libpersona( 6162): KNOX_SDCARD checking this for 10108
E/Zygote  ( 6162): MountEmulatedStorage()
I/libpersona( 6162): KNOX_SDCARD not a persona
E/Zygote  ( 6162): v2
,I/SELinux ( 6162): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6162): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6162): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6162 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1019): Killing 5163:com.google.android.gm/u0a99 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6162): TimaSignature is unavailable
,D/ActivityThread( 6162): Added TimaKeyStore provider
,W/libprocessgroup( 1019): failed to open /acct/uid_10099/pid_5163/cgroup.procs: No such file or directory
,I/MusicStore( 6162): Database version: 120
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6162): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6162): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6162): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ResourcesManager( 6162): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6162): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/wpa_supplicant( 1398): nl80211: Received scan results (5 BSSes)
,I/wpa_supplicant( 1398): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1398): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1398): Trying to associate with  'G700'
I/wpa_supplicant( 1398): Re-associate with C0.AA.48
D/WifiMonitor( 1019): didn't find BSSID Trying to associate with SSID 'NG700'
I/wpa_supplicant( 1398): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1398): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1019): mCursor = null
,V/JNIHelp ( 6162): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6162): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6162): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@96ff389: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6162): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6162): GMSCore installation verified
,I/ConfigStore( 6162): Config Database version: 1
,E/wpa_supplicant( 1398): Cmd 35605 not handled
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1398): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1398): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1398): Associated with C0.AA.48
I/wpa_supplicant( 1398): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1398): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1398): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, true,
D/Tethering( 1019): interfaceLinkStateChanged wlan0, true,
,D/Tethering( 1019): interfaceStatusChanged wlan0, true
E/Tethering( 1019): No numeric data
D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1019): clearTetheredNotification()
D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1019): mCursor = null
I/wpa_supplicant( 1398): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1398): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1398): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
V/NetworkStats( 1019): performPollLocked(flags=0x1)
I/wpa_supplicant( 1398): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/HotspotTile( 1177): updateTetherState():false, false
I/wpa_supplicant( 1398): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 1398): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1398): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1398): Blacklist: Clear (temp) 
D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
I/wpa_supplicant( 1398): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
D/Tethering( 1019): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1019): interfaceStatusChanged wlan0, true
V/NetworkStats( 1019): performPollLocked() took 2ms
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/WifiNative-wlan0( 1019): callSECApiVoid - ID [50]
,E/WifiConfigStore( 1019): setLastSelectedConfiguration -1
,D/ConnectivityService( 1019): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1019): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1019): updateNetworkInfo()
,D/ConnectivityService( 1019): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1019): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/WifiConfigStore( 1019): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/CommandListener(  279): Setting iface cfg
,E/WifiStateMachine( 1019): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
E/SMD     (  289): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/WifiNative-wlan0( 1019): do suspend false
,D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
,D/WifiP2pService( 1019): InactiveState{ what=143375 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=143375 }
,D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1019): getStreamVolume 3 index 70
,I/MediaRouter( 6162): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6162): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6190): MountEmulatedStorage()
E/Zygote  ( 6190): v2
I/libpersona( 6190): KNOX_SDCARD checking this for 10001
I/libpersona( 6190): KNOX_SDCARD not a persona
,I/SELinux ( 6190): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6190): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6190): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6190 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SQLiteLog( 1650): (10) POSIX Error : 11 SQLite Error : 3850
,I/GHttpClientFactory( 6162): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 6162): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6190): TimaSignature is unavailable
,D/ActivityThread( 6190): Added TimaKeyStore provider
,I/ActivityManager( 1019): Killing 5568:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,E/dhcpcd  ( 6207): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6207): version 5.5.6 starting
E/dhcpcd  ( 6207): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6215): MountEmulatedStorage(),
I/libpersona( 6215): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6215): v2
I/libpersona( 6215): KNOX_SDCARD not a persona
,I/SELinux ( 6215): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6215): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6215): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6215 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/ActivityManager( 1019): Killing 4134:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/dhcpcd  ( 6207): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6207): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6207): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6207): bssid match
,I/dhcpcd  ( 6207): wlan0: rebinding lease of 192.168.1.132
,W/libprocessgroup( 1019): failed to open /acct/uid_10139/pid_5568/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6215): TimaSignature is unavailable
,D/ActivityThread( 6215): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 6215): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1019): failed to open /acct/uid_10032/pid_4134/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6215): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6215): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6215): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6215): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6215): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6215): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6231): MountEmulatedStorage(),
,E/Zygote  ( 6231): v2
I/libpersona( 6231): KNOX_SDCARD checking this for 10008
,I/libpersona( 6231): KNOX_SDCARD not a persona
,I/ActivityManager( 1019): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6231 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6231): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Killing 5244:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/SELinux ( 6231): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6231): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6231): TimaSignature is unavailable
,D/ActivityThread( 6231): Added TimaKeyStore provider,
,I/ActivityManager( 1019): Killing 5619:com.samsung.helphub/1000 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3707): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 12 13:16:46 GMT+01:00 2016
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3707): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3707): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3707): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3707): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3707): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3707): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3707): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
I/KLMS-2.5.123: ( 3707): StateImplV2(): networkChangeListener().END
,E/Zygote  ( 6247): MountEmulatedStorage()
E/Zygote  ( 6247): v2
I/libpersona( 6247): KNOX_SDCARD checking this for 10031
I/libpersona( 6247): KNOX_SDCARD not a persona
,I/SELinux ( 6247): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1019): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6247 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6247): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6247): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3707): KLMSIntentService(): onDestroy()
,I/art     (  306): Explicit concurrent mark sweep GC freed 8683(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 24.613ms
,D/TimaKeyStoreProvider( 6247): TimaSignature is unavailable
,D/ActivityThread( 6247): Added TimaKeyStore provider
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 16.640ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 17.259ms
,I/SO_AGENT( 6247): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5668): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5668): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 5668): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5668): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5668): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 5722): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5722): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 5722): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5722): [SLFUCHKMGR] constructor called
,I/SA      ( 5722): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5722): [OR] == isSIMCardReady false ==
,I/SA      ( 5722): [SCU] == networkStateCheck == false
I/SA      ( 5722): [OR] onReceive END
,I/ActivityManager( 1019): Killing 5145:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,V/DownloadManager( 1228): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1623): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,W/libprocessgroup( 1019): failed to open /acct/uid_10014/pid_5244/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5619/cgroup.procs: No such file or directory
,D/daemonapp( 1696): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1623): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1623): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1623): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1623): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1623): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1623): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6264): MountEmulatedStorage(),
E/Zygote  ( 6264): v2
I/libpersona( 6264): KNOX_SDCARD checking this for 10121
,I/libpersona( 6264): KNOX_SDCARD not a persona
,I/SELinux ( 6264): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1019): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6264 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,I/SELinux ( 6264): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6264): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6264): TimaSignature is unavailable
,D/ActivityThread( 6264): Added TimaKeyStore provider
,W/ResourcesManager( 6264): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6264): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6264): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6264): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6264): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,W/libprocessgroup( 1019): failed to open /acct/uid_10032/pid_5145/cgroup.procs: No such file or directory
,I/QuickConnect( 6264): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6279): MountEmulatedStorage(),
E/Zygote  ( 6279): v2
I/libpersona( 6279): KNOX_SDCARD checking this for 10141
I/libpersona( 6279): KNOX_SDCARD not a persona
I/SELinux ( 6279): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6279): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6279): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6279 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 5653:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6279): TimaSignature is unavailable
,D/ActivityThread( 6279): Added TimaKeyStore provider
,W/ResourcesManager( 6279): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6279): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6279): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6279): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1019): failed to open /acct/uid_10087/pid_5653/cgroup.procs: No such file or directory
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/BadgeProvider( 5774): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/BadgeProvider( 5774): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5774): sendNotify, [notify] : null
D/BadgeProvider( 5774): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5774): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5774): update, [UpdateCount] : 1
,D/Launcher.Model( 1478): reloadBadges entered.
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6302 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,E/Zygote  ( 6302): MountEmulatedStorage()
,I/libpersona( 6302): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6302): v2
I/libpersona( 6302): KNOX_SDCARD not a persona
,I/SELinux ( 6302): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6302): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6302): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6302): TimaSignature is unavailable
,D/ActivityThread( 6302): Added TimaKeyStore provider
,I/dhcpcd  ( 6207): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,D/SecurityLogAgent( 6302): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6302): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6302): StateMachine : Current State = 1
,D/SecurityLogAgent( 6302): StateMachine : Changed Current State = 1
,I/ActivityManager( 1019): Killing 5259:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 58209(3MB) AllocSpace objects, 8(180KB) LOS objects, 33% free, 24MB/36MB, paused 2.903ms total 190.945ms,
,I/dhcpcd  ( 6207): wlan0: leased 192.168.1.132 for 86400 seconds
W/ActivityManager( 1019): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/iu.Environment( 1927): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1927): num queued entries: 0
,I/iu.UploadsManager( 1927): num updated entries: 0
,I/iu.SyncManager( 1927): NEXT; no task
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1927): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6330): MountEmulatedStorage(),
,E/Zygote  ( 6330): v2
I/libpersona( 6330): KNOX_SDCARD checking this for 10032
I/SELinux ( 6330): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/libpersona( 6330): KNOX_SDCARD not a persona
,I/SELinux ( 6330): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6330): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6330 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 6119): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager( 1019): Killing 5707:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,W/libprocessgroup( 1019): failed to open /acct/uid_10029/pid_5259/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6330): TimaSignature is unavailable
,D/ActivityThread( 6330): Added TimaKeyStore provider
,W/libprocessgroup( 1019): failed to open /acct/uid_10148/pid_5707/cgroup.procs: No such file or directory
,E/SPPClientService( 6330): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6330): [PushClientApplication] Push log off : This is Ship build version
E/SPPClientService( 6330): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6330): [SystemStateMoniter] Current Time : 161813
,E/SPPClientService( 6330): [SystemStateMoniter] No Connect : true
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6330): PushLog.txt file is not deleted.
D/SPPClientService( 6330): PushLog.txt file is not deleted.
D/SPPClientService( 6330): ============PushLog. stop!
,E/Zygote  ( 6361): MountEmulatedStorage(),
E/Zygote  ( 6361): v2
I/libpersona( 6361): KNOX_SDCARD checking this for 10110
I/libpersona( 6361): KNOX_SDCARD not a persona,
I/SELinux ( 6361): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6361 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 6361): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Killing 5741:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,E/SELinux ( 6361): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/TimaKeyStoreProvider( 6361): TimaSignature is unavailable
E/SPPClientService( 6330): [[SystemStateMonitorService]] No Active Internet
D/ActivityThread( 6361): Added TimaKeyStore provider
,W/libprocessgroup( 1019): failed to open /acct/uid_10152/pid_5741/cgroup.procs: No such file or directory
,E/WifiNative-wlan0( 1019): do suspend true
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6361): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6361): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6361): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6361):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6361):   adb logcat -s GAv4
,D/WifiP2pService( 1019): InactiveState{ what=143375 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1019): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1019): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/GAv4    ( 6361): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/WifiNative-wlan0( 1019): callSECApiInt - ID [210]
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,E/ConnectivityService( 1019): updateNetworkInfo()
,W/ContextImpl( 6361): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/ConnectivityService( 1019): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1019): Adding iface wlan0 to network 503
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6361): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
D/WifiWatchdogStateMachine( 1019): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1019): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
D/WifiWatchdogStateMachine.DnsResolver( 1019): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1019): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1019): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,W/GAv4    ( 6361): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/WifiTrafficPoller( 1019): evaluateTrafficStatsPolling
W/GAv4    ( 6361): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService( 1019): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1019): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1019): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1019): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1019): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 1019): LTETest block dns file not exists
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1019): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 1019): updateNetworkInfo()
E/ConnectivityService( 1019): updateNetworkInfo()
,D/ConnectivityService( 1019): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1019): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1019): rematching NetworkAgentInfo [WIFI () - 503]
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/System.out( 1019): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService( 1019):    accepting network in place of null
,E/WifiStateMachine( 1019): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WIFI_P2P( 1019): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1446): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,I/WifiTrafficPoller( 1019): evaluateTrafficStatsPolling
,D/TelephonyNetworkFactory( 1446): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WifiTrafficPoller( 1019): mBoosterFLAG : 0
E/CSLegacyTypeTracker( 1019): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1019): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
I/WifiTrafficPoller( 1019): current booster mode : FullMode
,D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 1000
E/WifiStateMachine( 1019): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WIFI    ( 1019): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/WifiNative-wlan0( 1019): callSECApiVoid - ID [212]
,D/ConnectivityService( 1019): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1019): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/EntConnectivity( 1019): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,D/Tethering( 1019): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1019): MasterInitialState.processMessage what=3
,V/NetworkStats( 1019): updateIfacesLocked()
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
,V/NetworkStats( 1019): performPollLocked() took 3ms
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/System.out( 1019): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 12 Jan 2016 12:16:47 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452601007958], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452601007939]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Don't send network conditions - lacking user consent.,
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Validated
D/ConnectivityService( 1019): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1019): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1019): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1019): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
,D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte,
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6361): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6361): Time to load native libraries: 2 ms (timestamps 2285-2287)
,I/LibraryLoader( 6361): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6361): Binding Chromium to main looper Looper (main, tid 1) {22ba93c4}
,I/LibraryLoader( 6361): Expected native library version number "",actual native library version number ""
,I/chromium( 6361): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6361): Initializing chromium process, singleProcess=true
,W/art     ( 6361): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6361): ApplicationContext is null in ApplicationStatus
,W/chromium( 6361): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6361): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6361): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6361): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6361): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6361): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6361): Local Branch: 
I/Adreno-EGL( 6361): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6361): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6361):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/NSApplication( 6361): Starting up...
,W/AudioManagerAndroid( 6361): Requires BLUETOOTH permission
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6422): MountEmulatedStorage()
,E/Zygote  ( 6422): v2
,I/libpersona( 6422): KNOX_SDCARD checking this for 10077
I/libpersona( 6422): KNOX_SDCARD not a persona
,I/SELinux ( 6422): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6422 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1019): Killing 5605:com.android.mms/u0a41 (adj 15): empty #31
I/SELinux ( 6422): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6422): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6422): TimaSignature is unavailable
,D/ActivityThread( 6422): Added TimaKeyStore provider
,D/CountryDetector( 1019): No listener is left
,W/libprocessgroup( 1019): failed to open /acct/uid_10041/pid_5605/cgroup.procs: No such file or directory
,D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1019): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/WaitQueueForNetworkActivate( 5953): notifyNetworkActivated
,I/NetworkMonitor( 6162): type=WIFI subType= reason=null isConnected=true
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
,W/ContextImpl( 5953): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1019): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5953): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5953): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5953): exit::IDLE
D/InitializeManagerStateMachine( 5953): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5953): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5953): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5953): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5953): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5953): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5953): entry::SUCCESS
D/hcjo    ( 5953): AutoUpdateManager:INITCHECK:onInitializeSuccess
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/hcjo    ( 5953): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5953): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5953): exit::SUCCESS
D/InitializeManagerStateMachine( 5953): entry::IDLE
,I/Hs20UtilService( 2065): Starting #10
,I/Hs20UtilService( 2065): Message received 5007
,D/NearbySettings( 1361): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1361): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1361): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1361): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1361): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1361): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 1019): Killing 4392:com.google.android.gms.wearable/u0a11 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2065): Starting #11
,I/Hs20UtilService( 2065): Message received 5007
,D/NearbySettings( 1361): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1361): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2065): Starting #12
,I/Hs20UtilService( 2065): Message received 5007
,D/NearbySettings( 1361): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1361): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1361): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1361): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1361): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1361): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2065): Starting #13
,I/Hs20UtilService( 2065): Message received 5007
,D/NearbySettings( 1361): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1361): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1019): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1019): mCursor = null
,W/libprocessgroup( 1019): failed to open /acct/uid_10011/pid_4392/cgroup.procs: No such file or directory
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1019): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5638): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5638): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5638): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5638): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1019): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1019): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1019): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6162): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT( 6215): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6215): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6215): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6215): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService( 1019): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019
,D/SRIB_DCS( 1177): log_dcs ThreadedRenderer::initialize entered! 
,I/DBG_POLICYDM( 5668): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5668): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5668): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5668): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5668): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_POLICYDM( 5668): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6231): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6231): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 3707): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 12 13:16:48 GMT+01:00 2016
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3707): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3707): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3707): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3707): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3707): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3707): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3707): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3707): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3707): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.5.123: ( 3707): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3707): StateImplV2(): networkChangeListener().END
,D/ConnectivityService( 1019): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/KLMS-2.5.123: ( 3707): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 5668): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5668): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5668): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,I/SA      ( 5722): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5722): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5722): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,E/DBG_POLICYDM( 5668): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 5722): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5722): [OR] == isSIMCardReady false ==
,I/SA      ( 5722): [SCU] == networkStateCheck == true
,I/SA      ( 5722): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5722): isChinaCountryCode : false
I/SA      ( 5722): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5722): [OR] == networkStateCheck true ==
,I/SA      ( 5722): [OR] GetMyCountryZoneTask
,I/SA      ( 5722): [OR] onReceive END
,I/DBG_POLICYDM( 5668): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 5722): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 1228): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 5668): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,D/accuweather( 1623): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5668): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/SA      ( 5722): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/DBG_POLICYDM( 5668): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
I/SA      ( 5722): [SSP] query invoked
,I/DBG_POLICYDM( 5668): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5668): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,V/AlarmManager( 1019): waitForAlarm result :4
,I/DBG_POLICYDM( 5668): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5668): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/daemonapp( 1696): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,I/DBG_POLICYDM( 5668): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,D/accuweather( 1623): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1623): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1623): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1623): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5668): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/SecContentProvider2( 1019): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1019): mCursor = null
,I/SA      ( 5722): [TPMU] GetMccFromDB : null
I/SA      ( 5722): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5722): [TPM] isNoProxy(default) : true
,D/accuweather( 1623): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1623): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/QuickConnect( 6264): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6264): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6264): PeriphStartReceiver.onReceive - no need to start
,E/File    ( 5722): fail readDirectory() errno=2
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,E/DBG_POLICYDM( 5668): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/SecurityLogAgent( 6302): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6302): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6302): StateMachine : Current State = 1
,D/SecurityLogAgent( 6302): StateMachine : Changed Current State = 1
,I/DBG_POLICYDM( 5668): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5668): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,I/iu.Environment( 1927): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1927): num queued entries: 0
,I/iu.UploadsManager( 1927): num updated entries: 0
,I/iu.SyncManager( 1927): NEXT; no task
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1927): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1927): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6330): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6330): [SystemStateMoniter] Current Time : 163252
,E/SPPClientService( 6330): [SystemStateMoniter] No Connect : false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 6119): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6119): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6119): (HTTPLog)-Static: isShipBuild true
I/System.out( 6119): (HTTPLog)-Thread-1038-283263363: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6119): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10102
,I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,I/System.out( 6119): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/hcjo    ( 5953): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5953): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5953): exit::IDLE
D/InitializeManagerStateMachine( 5953): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5953): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 5953): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5953): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5953): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5953): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5953): entry::SUCCESS
D/hcjo    ( 5953): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5953): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5953): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5953): exit::SUCCESS
D/InitializeManagerStateMachine( 5953): entry::IDLE
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Kids    ( 1927): [AccountUtils] Account not ready
W/Kids    ( 1927): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1927): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1927): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1927): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1927): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1927): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1927): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1927): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1927): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1927): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1927): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1927): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) ,
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,I/Babel   ( 6119): connection state changed from DISCONNECTED to CONNECTED
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/GCM     ( 1650): Connected
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1650): Message class com.google.f.a.a.p
,I/SA      ( 5722): [RC New] Execute method=[GET] start
,I/SA      ( 5722): [RC New] Security=[true]
,I/System.out( 5722): Thread-960(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5722): Thread-960(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5722): Thread-960(ApacheHTTPLog):isShipBuild true
I/System.out( 5722): Thread-960(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5722): Thread-960(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10036
,D/ConnectivityService( 1019): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1019): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295
D/ConnectivityService( 1019): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6060): BLE is supported
I/jxcore-log( 6060): 
,I/SA      ( 5722): [RC New] [v2liruge] api execute + 615
,I/SA      ( 5722): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5722): AsyncTask #1 calls detatch()
,I/SA      ( 5722): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5722): [OCP] update openData : PL
,I/SA      ( 5722): [TPMU] getNetworkMcc : 
,I/SA      ( 5722): [SCU] saveMccToPreferece Start
,I/SA      ( 5722): [SCU] RegionMCC : 260
,I/SA      ( 5722): [SSP] query invoked
,I/SA      ( 5722): [TPMU] GetMccFromDB : null
,I/SA      ( 5722): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5722): [SCU] saveMccToPreferece End
,I/SA      ( 5722): [RC New] executeRequest [v2liruge] end. 674
I/SA      ( 5722): [RC New] Execute end
,I/SA      ( 5722): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5722): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 6207): wlan0: sending IPv6 Router Solicitation
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
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
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6473): MountEmulatedStorage(),
E/Zygote  ( 6473): v2
I/libpersona( 6473): KNOX_SDCARD checking this for 10011
,I/libpersona( 6473): KNOX_SDCARD not a persona
,I/SELinux ( 6473): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6473 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/MusicLeanback( 6162): Conditions not met for autocaching. okToAttempt=false,
I/MusicLeanback( 6162): Stop autocaching.
I/SELinux ( 6473): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6473): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/TimaKeyStoreProvider( 6473): TimaSignature is unavailable
,D/ActivityThread( 6473): Added TimaKeyStore provider
,W/ResourcesManager( 6473): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6473): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6473): VM with version 2.1.0 has multidex support
,I/MultiDex( 6473): install
I/MultiDex( 6473): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6473): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6473): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6473): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c705dfb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6473): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1019): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1019): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1019): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
,I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1650): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1650): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1927): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
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
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
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
,D/WearableService( 6473): callingUid 10011, callindPid: 6473
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1927): Restart initialization of location
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1726): Explicit concurrent mark sweep GC freed 17655(1011KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 8MB/13MB, paused 1.332ms total 74.627ms
,E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@89ef33e)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1650): Explicit concurrent mark sweep GC freed 25642(1478KB) AllocSpace objects, 8(162KB) LOS objects, 39% free, 7MB/12MB, paused 1.004ms total 41.145ms
,E/MDM     ( 1726): [193] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6162): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6162): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SMD     (  289): DCD OFF
,I/SurfaceFlinger(  258): id=14 Removed Uoast (8/9),
,I/SurfaceFlinger(  258): id=14 Removed Uoast (-2/9),
,D/PowerManagerService( 1019): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1019) eventTime = 166412
,D/PowerManagerService( 1019): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019 (0x0)
,D/PowerManagerService( 1019): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1019, ws=WorkSource{10049}) (elapsedTime=3479)
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5638): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5638): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5638): [GetString-S]
,I/ReactiveServiceManager( 5638): Supported : 1
,D/QSEECOMAPI: ( 1019): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1019): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1019): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1019): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1019): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1019): handleString: Failed to handle string(-4)
E/terrier ( 1019): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5638): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5638): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5638): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5638): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5638): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5638): [ensureRegistration] - No Samsung account
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,E/Watchdog( 1019): !@Sync 5
,I/dhcpcd  ( 6207): wlan0: sending IPv6 Router Solicitation
,V/AlarmManager( 1019): waitForAlarm result :4
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5326): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5326): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5326): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  289): DCD OFF
,I/ActivityManager( 1019): Killing 5786:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,W/libprocessgroup( 1019): failed to open /acct/uid_10042/pid_5786/cgroup.procs: No such file or directory,
,V/AlarmManager( 1019): waitForAlarm result :4
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 42095(2MB) AllocSpace objects, 7(116KB) LOS objects, 33% free, 24MB/36MB, paused 2.454ms total 184.508ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
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
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1650): Vacuum at: now=1452601017987 tag=VacuumService
,D/Batterystats( 1927): User is not opted-in to Usage & Diagnostics.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 1650): Using platform SSLCertificateSocketFactory
,E/SMD     (  289): DCD OFF
,W/Uploader( 1650): No account for auth token provided
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1650): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1650): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1650): (HTTPLog)-Static: isShipBuild true
I/System.out( 1650): (HTTPLog)-Thread-189-494303143: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 1650): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,I/System.out( 1650): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1650): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1650, getuid(): 10011
,I/qtaguid ( 1650): Tagging socket 61 with tag 120100000000{4609,0} for uid -1, pid: 1650, getuid(): 10011
,W/Uploader( 1650): No account for auth token provided
,I/System.out( 1650): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1650): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1650, getuid(): 10011
,W/Uploader( 1650): No account for auth token provided
,I/System.out( 1650): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1650): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1650, getuid(): 10011
,W/Uploader( 1650): No account for auth token provided
,I/System.out( 1650): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1650): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1650, getuid(): 10011
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5953): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5953): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5953): entry::CHECK_TIMEOUT_FOR_UPDATE
,I/dhcpcd  ( 6207): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6207): wlan0: no IPv6 Routers available
D/hcjo    ( 5953): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5953): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 5953): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5953): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5953): entry::IDLE
,W/Uploader( 1650):  no longer exists, so no auth token.
,I/System.out( 1650): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1650): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1650, getuid(): 10011
,W/Uploader( 1650): No account for auth token provided
,I/System.out( 1650): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1650): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1650, getuid(): 10011
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1650): Background sticky concurrent mark sweep GC freed 27336(1432KB) AllocSpace objects, 53(3MB) LOS objects, 36% free, 8MB/12MB, paused 5.300ms total 52.314ms
,I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
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
,E/Uploader( 1650): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1650): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1650): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1650): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1650): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1650): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1650): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1650): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1650): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1650): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1650): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1650): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1650): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1650): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1650): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1650, getuid(): 10011
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5953): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5953): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5953): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5953): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 5953): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5953): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5953): entry::IDLE
,E/SQLiteLog( 1650): (10) POSIX Error : 11 SQLite Error : 3850
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 105s ago
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1019): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
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
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1019): waitForAlarm result :4
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5326): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5326): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5326): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 6
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :4,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/PowerManagerService( 1019): [PWL] Off : 140s ago
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 7
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1019): waitForAlarm result :8
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 1019): stay LED for fully charged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/PowerManagerService( 1019): [PWL] Off : 180s ago
,E/Watchdog( 1019): !@Sync 8
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,I/BooksSync( 5981): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 5981): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,E/SMD     (  289): DCD OFF
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
,I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5981): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5981): Soft error
E/BooksSync( 5981): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5981): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 5981): Sync error
E/BooksSync( 5981): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5981): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5981): Finished books sync
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 286231, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 9
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,V/AlarmManager( 1019): waitForAlarm result :8
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 225s ago
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1019): initializing...
,I/TLC_TIMA_PKM_initialize( 1019): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1019): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1019): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1019): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1019): aligned max_sendmsg_size = 262208 = 0x40040,
I/TZ: qc_tlc_communication( 1019): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1019): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1019): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1019): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1019): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1019): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1019): Trustlet response is completed
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,E/SMD     (  289): DCD OFF
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/Watchdog( 1019): !@Sync 10
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF,
,I/jxcore-log( 6060): Connected to the server!
I/jxcore-log( 6060): 
,I/chromium( 6060): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2654): Disconnected process message: 10,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,V/AlarmManager( 1019): waitForAlarm result :4
,I/BooksSync( 5981): Starting books sync for 61035162, extras: ade
,E/SMD     (  289): DCD OFF,
,I/BooksConfig( 5981): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5981): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5981): Soft error
E/BooksSync( 5981): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5981): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 5981): Sync error
E/BooksSync( 5981): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5981): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5981): Finished books sync
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 317615, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 11
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 275s ago,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 2
,V/AlarmManager( 1019): waitForAlarm result :8,
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found,
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice,
D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/GLSActivity( 1650): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1650): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1650): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1650): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1650): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1650): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1650): 	at android.os.Binder.execTransact(Binder.java:461)
,E/PlayEventLogger( 5326): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5326): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5326): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5326): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5326): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5326): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5326): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 5326): Ignoring header User-Agent because its value was null.
,I/System.out( 5326): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5326): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5326): (HTTPLog)-Static: isShipBuild true
I/System.out( 5326): (HTTPLog)-Thread-893-403749867: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5326): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  289): DCD OFF
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10026
,I/System.out( 5326): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,E/SMD     (  289): DCD OFF
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 12
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 13
,I/PowerManagerService( 1019): [PWL] Off : 330s ago,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,V/AlarmManager( 1019): waitForAlarm result :4
,I/BooksSync( 5981): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 5981): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 49237(3MB) AllocSpace objects, 102(1650KB) LOS objects, 33% free, 24MB/36MB, paused 2.494ms total 153.327ms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found,
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5981): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5981): Soft error
E/BooksSync( 5981): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5981): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 5981): Sync error
E/BooksSync( 5981): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5981): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 5981): Finished books sync
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 408773, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5,
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1019): !@Sync 14,
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged,
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD OFF
,I/jxcore-log( 6060): --- start :testFindPeers.js---
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): testFindPeers created [object Object]
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): serverPort is 8876
I/jxcore-log( 6060): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): setDiscoveryMode: Mode set to BLE,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): start: Peer ID: 08:EC:A9:50:75:41, peer name: A3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6060): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6060): initialize: My bluetooth address is 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6060): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"},
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6060): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6060): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]},
,D/BluetoothSocket( 6060): bindListen(), new LocalSocket 
D/BluetoothSocket( 6060): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6060): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a9e377a
D/BluetoothSocket( 6060): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): start: OK
I/io.jxcore.node.ConnectionHelper( 6060): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): start: Peer ID: 08:EC:A9:50:75:41, peer name: A3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6060): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6060): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): start: {"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6060): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1019): InactiveState{ what=139292 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6060): start: OK
,I/jxcore-log( 6060): StartBroadcasting started ok
I/jxcore-log( 6060): 
D/WifiP2pService( 1019): P2pEnabledState add service
,I/chromium( 6060): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 6060): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onWifiStateChanged: State changed to 2
I/io.jxcore.node.ConnectionHelper( 6060): onDiscoveryManagerStateChanged: RUNNING
,D/WifiP2pService( 1019): add a new client
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6060): Local service added successfully
,D/WifiP2pService( 1019): InactiveState{ what=139265 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139265 }
,D/WifiService( 1019): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1019): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1019): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1398): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1019): discovery change broadcast true,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,E/SMD     (  289): DCD OFF
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2412,
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 7E.18.23 p2p_dev_addr=7E.18.23 pri_dev_type=10-0050F204-5  ' A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
,D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 5 device(s) discovered
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 5 device(s) discovered
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1019): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 5 device(s) discovered
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad,
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1019): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1019): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pManager( 6060): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service request added successfully
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 101,9):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1019): InactiveState{ what=139310 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1019): P2pEnabledState discover services
,D/WifiService( 1019): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1019): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiStateMachine( 1019): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1398): USE_NETWORK : USE_NETWORK OFF
I/wpa_supplicant( 1398): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service discovery started successfully
,I/wpa_supplicant( 1398): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1398): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1019): InactiveState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 8 device(s) discovered
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1019): InactiveState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 8 device(s) discovered,
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1019): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 8 device(s) discovered
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceLi,stChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1],
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 6060): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
I/jxcore-log( 6060): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"A5-1","peerAvailable":true}]
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 6060): 
,D/WifiP2pService( 1019): InactiveState{ what=147494 },
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/WifiP2pService( 1019): P2pEnabledState receive service response
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)],
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 6060): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
,I/jxcore-log( 6060): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"Thali Test (Galaxy A5)","peerAvailable":true}]
I/jxcore-log( 6060): 
I/jxcore-log( 6060): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 6060): 
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [44:80:EB:7B:5A:05 XT1072]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 XT1072]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
D/io.jxcore.node.ConnectionHelper( 6060): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 XT1072] is available
I/jxcore-log( 6060): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"XT1072","peerAvailable":true}]
I/jxcore-log( 6060): 
I/jxcore-log( 6060): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log( 6060): 
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,D/io.jxcore.node.ConnectionHelper( 6060): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] is available
I/jxcore-log( 6060): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"G3-1","peerAvailable":true}]
I/jxcore-log( 6060): 
I/jxcore-log( 6060): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 6060): 
E/SMD     (  289): DCD OFF
,D/WifiP2pService( 1019): InactiveState{ what=147494 },
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 6060): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
I/jxcore-log( 6060): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"G3s-1","peerAvailable":true}]
I/jxcore-log( 6060): 
I/jxcore-log( 6060): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 6060): 
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 6060): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
I/jxcore-log( 6060): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"Thali Test (Galaxy A3)","peerAvailable":true}]
I/jxcore-log( 6060): 
I/jxcore-log( 6060): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 6060): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
D/WifiP2pService( 1019): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 Nexus 5]
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
D/WifiP2pService( 1019): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 Nexus 5]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
D/io.jxcore.node.ConnectionHelper( 6060): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 Nexus 5] is available
I/jxcore-log( 6060): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"Nexus 5","peerAvailable":true}]
I/jxcore-log( 6060): 
I/jxcore-log( 6060): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 6060): 
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiDisplayController( 1019): Received list of peers.
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
,D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1019): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019): DefaultState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
,I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 6060): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
I/jxcore-log( 6060): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"G4-1","peerAvailable":true}]
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 6060): 
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab,: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 11 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 6060): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
I/jxcore-log( 6060): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"S5-1","peerAvailable":true}]
I/jxcore-log( 6060): 
I/jxcore-log( 6060): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 6060): 
,E/SMD     (  289): DCD OFF,
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 },
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  289): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1019): !@Sync 15
,I/PowerManagerService( 1019): [PWL] Off : 390s ago
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 2,
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
,D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): restart: Restarting...
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): InactiveState{ what=139307 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139307 }
,D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): P2pEnabledState clear service request
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1019): InactiveState{ what=139301 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1019): P2pEnabledState add service request
,D/WifiP2pManager( 6060): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service request added successfully
,D/WifiP2pService( 1019): InactiveState{ what=139310 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1019): P2pEnabledState discover services
,D/WifiStateMachine( 1019): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1019): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1019): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1398): USE_NETWORK : USE_NETWORK OFF,
I/wpa_supplicant( 1398): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service discovery started successfully
,E/SMD     (  289): DCD OFF,
,I/wpa_supplicant( 1398): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1398): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=147477 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 },
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1019): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
,D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [44:80:EB:7B:5A:05 XT1072]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 XT1072]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 XT1072] already in the list, will not add again
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 G3s-1] already in the list, will not add again
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 6060): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 Note4-1] is available
,I/jxcore-log( 6060): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"Note4-1","peerAvailable":true}]
I/jxcore-log( 6060): 
I/jxcore-log( 6060): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 6060): 
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/bootchecker(  312): bootchecker wake up!!
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/BatteryService( 1019): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1019): !@Sync 16
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): setState: RESTARTING
,D/WifiP2pService( 1019): InactiveState{ what=139268 }
,I/wpa_supplicant( 1398): P2P-FIND-STOPPED 
,D/WifiP2pService( 1019): InactiveState{ what=147493 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1019): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): Start timer timeout, starting now...
,D/WifiP2pService( 1019): InactiveState{ what=139265 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139265 }
D/WifiService( 1019): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1019): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1019): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1398): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1019): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): P2P device discovery started successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,E/SMD     (  289): DCD OFF,
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437,
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 7E.18.23 p2p_dev_addr=7E.18.23 pri_dev_type=10-0050F204-5  ' A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1019): InactiveState{ what=147477 }
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019): Received list of peers.
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true,
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
,D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1019): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1019): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): restart: Restarting...
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1019): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
,D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 6060): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiP2pService( 1019): InactiveState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service request added successfully
,D/WifiP2pService( 1019): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1019): P2pEnabledState clear service request
D/WifiP2pService( 1019): InactiveState{ what=139301 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1019): P2pEnabledState add service request
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/WifiP2pService( 1019): InactiveState{ what=139310 },
D/WifiP2pService( 1019): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1019): P2pEnabledState discover services
,D/WifiStateMachine( 1019): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1019): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1019): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1398): USE_NETWORK : USE_NETWORK OFF,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service discovery started successfully
,I/wpa_supplicant( 1398): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1019): InactiveState{ what=147477 },
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress,: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1019): !@Sync 17
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 455s ago,
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 5981): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 5981): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5981): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5981): Soft error
E/BooksSync( 5981): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5981): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 5981): Sync error
E/BooksSync( 5981): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5981): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 5981): Finished books sync
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 533485, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/jxcore-log( 6060): timeout now,
I/jxcore-log( 6060): 
I/jxcore-log( 6060): weAreDoneNow
I/jxcore-log( 6060): 
I/jxcore-log( 6060): done, now sending data to server
I/jxcore-log( 6060): 
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): setState: RESTARTING
,D/WifiP2pService( 1019): InactiveState{ what=139268 }
I/wpa_supplicant( 1398): P2P-FIND-STOPPED 
,D/WifiP2pService( 1019): InactiveState{ what=147493 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1019): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): Start timer timeout, starting now...
,D/WifiP2pService( 1019): InactiveState{ what=139265 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139265 }
D/WifiService( 1019): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1019): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiStateMachine( 1019): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1398): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): P2P device discovery started successfully,
D/WifiP2pService( 1019): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1019): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerA,ddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): restart: Restarting...
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1019): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1019): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1019): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pService( 1019): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 6060): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service request added successfully
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1019): InactiveState{ what=139310 },
D/WifiStateMachine( 1019): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiP2pService( 1019): P2pEnabledState{ what=139310 },
D/WifiStateMachine( 1019): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiP2pService( 1019): P2pEnabledState discover services
D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [13]
D/WifiService( 1019): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/wpa_supplicant( 1398): USE_NETWORK : USE_NETWORK OFF
I/wpa_supplicant( 1398): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service discovery started successfully
,I/wpa_supplicant( 1398): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1398): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1019): InactiveState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiP2pService( 1019): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 6060): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
,E/Watchdog( 1019): !@Sync 18,
,I/Atfwd_Sendcmd(  315): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  315): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 7E.18.23 p2p_dev_addr=7E.18.23 pri_dev_type=10-0050F204-5  ' A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 },
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1019): InactiveState{ what=147477 },
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1019): DefaultState{ what=139283 },
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019): DefaultState{ what=139283 },
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiDisplayController( 1019): Received list of peers.
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false,
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437,
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/IOP_DB_BT( 2654): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab,
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_VER, value 0:0
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2654): db_query_execute: result 1
,D/IOP_DB_BT( 2654): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_VER, value 0:0
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2654): db_query_execute: result 1
W/bt-btif ( 2654): info:x10
,D/        ( 2654): remote version info [7c:f9:0e:37:96:ab]: 0, 0, 0
,E/BluetoothRemoteDevices( 2654): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.NAME_CHANGED
,I/jxcore-log( 6060): teardown,
I/jxcore-log( 6060): 
I/jxcore-log( 6060): testFindPeers stopped
I/jxcore-log( 6060): 
,I/io.jxcore.node.ConnectionHelper( 6060): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): shutdown
,D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@1485146, channel: 6, state: LISTENING
D/BluetoothSocket( 6060): close() this: android.bluetooth.BluetoothSocket@1485146, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a9e377a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@36b21f07mSocket: android.net.LocalSocket@15b58834 impl:android.net.LocalSocketImpl@1a03065d fd:FileDescriptor[109]
D/BluetoothSocket( 6060): Closing mSocket: android.net.LocalSocket@15b58834 impl:android.net.LocalSocketImpl@1a03065d fd:FileDescriptor[109]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6060): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): setState: NOT_STARTED,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): stop: Stopping P2P device discovery...
,D/WifiP2pService( 1019): InactiveState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): setState: NOT_INITIALIZED
D/WifiP2pService( 1019): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService( 1019): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6060): release: No more listeners, de-initializing...
D/WifiP2pService( 1019): InactiveState{ what=139268 }
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6060): release: The given listener does not exist in the list
D/WifiP2pService( 1019): InactiveState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6060): release: No more listeners, de-initializing...
D/WifiP2pService( 1019): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): setState: NOT_STARTED
D/WifiP2pService( 1019): P2pEnabledState clear service request
I/jxcore-log( 6060): StopBroadcasting went ok
I/jxcore-log( 6060): 
D/WifiP2pService( 1019): remove channel information from framework
I/wpa_supplicant( 1398): P2P-FIND-STOPPED 
,I/jxcore-log( 6060): --- start :testSendData.js---
I/jxcore-log( 6060): 
I/jxcore-log( 6060): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":13}bt-address length : 12
I/jxcore-log( 6060): 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): onServerStopped
D/WifiP2pService( 1019): InactiveState{ what=147493 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1019): discovery change broadcast false
,I/jxcore-log( 6060): daya100000
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): check server
I/jxcore-log( 6060): 
I/jxcore-log( 6060): serverPort is 36121
I/jxcore-log( 6060): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): start: Peer ID: 08:EC:A9:50:75:41, peer name: A3-1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6060): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6060): initialize: My bluetooth address is 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6060): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6060): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6060): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[110]}
D/BluetoothSocket( 6060): bindListen(), new LocalSocket 
D/BluetoothSocket( 6060): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6060): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11c7a4a3
D/BluetoothSocket( 6060): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): start: OK
I/io.jxcore.node.ConnectionHelper( 6060): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): start: Peer ID: 08:EC:A9:50:75:41, peer name: A3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6060): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6060): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): start: {"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6060): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1019): InactiveState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6060): start: OK
,I/jxcore-log( 6060): StartBroadcasting started ok
I/jxcore-log( 6060): 
,D/WifiP2pService( 1019): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 1019): P2pEnabledState add service
D/WifiP2pService( 1019): add a new client
,D/WifiP2pService( 1019): InactiveState{ what=139265 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139265 }
D/WifiService( 1019): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1019): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1019): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1398): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1019): discovery change broadcast true
,I/jxcore-log( 6060): [ { address: 'E0:DB:10:14:E2:C0', tryCount: 0 },
I/jxcore-log( 6060):   { address: '08:EC:A9:50:76:27', tryCount: 0 },
I/jxcore-log( 6060):   { address: '58:3F:54:73:64:C0', tryCount: 0 },
I/jxcore-log( 6060):   { address: '7C:F9:0E:51:18:22', tryCount: 0 },
I/jxcore-log( 6060):   { address: '34:FC:EF:11:AE:67', tryCount: 0 },
I/jxcore-log( 6060):   { address: '7C:F9:0E:37:96:AB', tryCount: 0 },
I/jxcore-log( 6060):   { address: '7C:F9:0E:34:8A:A0', tryCount: 0 },
I/jxcore-log( 6060):   { address: 'F8:95:C7:87:85:54', tryCount: 0 },
I/jxcore-log( 6060):   { address: 'B0:C5:59:3F:75:69', tryCount: 0 },
I/jxcore-log( 6060):   { address: '44:80:EB:7B:5A:05', tryCount: 0 },
I/jxcore-log( 6060):   { address: '00:F4:6F:30:E0:6C', tryCount: 0 },
I/jxcore-log( 6060):   { address: 'F8:95:C7:87:3C:51', tryCount: 0 } ]
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): startWithNextDevice
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): do fake peer & start
I/jxcore-log( 6060): 
I/jxcore-log( 6060): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:23:30.606Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:23:30.607Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:23:30.607Z SendDataConnector.js: do connect now
I/jxcore-log( 6060): 
,I/io.jxcore.node.ConnectionHelper( 6060): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
,D/io.jxcore.node.ConnectionHelper( 6060): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): connect: [E0:DB:10:14:E2:C0 Note4-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): onConnecting: null E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 6060): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 1045)
I/jxcore-log( 6060): 2016-01-12T12:23:30.615Z SendDataTCPServer.js: TCP/IP server is bound to port: 36121
I/jxcore-log( 6060): 
I/io.jxcore.node.ConnectionHelper( 6060): onConnectionManagerStateChanged: NOT_STARTED
I/chromium( 6060): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6060): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6060): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): P2P device discovery stopped successfully
,I/chromium( 6060): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6060): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onWifiStateChanged: State changed to 2
I/io.jxcore.node.ConnectionHelper( 6060): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6060): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/WifiP2pService( 1019): InactiveState{ what=139268 }
I/wpa_supplicant( 1398): P2P-FIND-STOPPED 
,D/WifiP2pService( 1019): InactiveState{ what=147493 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1019): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): setState: RESTARTING
,D/WifiP2pService( 1019): InactiveState{ what=139268 }
,D/BluetoothUtils( 6060): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 6060): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2654): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 6060): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 2654): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,D/SecContentProvider( 1019): uri = 4 selection = bluetoothLogForRemote
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.CLASS_CHANGED
,E/bt-btif ( 2654): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2654): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2654): isSecureModeOn:false
I/BluetoothBondStateMachine( 2654): Entering PendingCommandState State
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 1361): onReceive
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5887): BTStateChangeCB is registed
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
E/BluetoothHeadset( 5887): BluetoothHeadset service is binded
,D/GMFPReceiver( 5887): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5887): jangil::setProperties()
,D/GMFPReceiver( 5887): jangil::printBTStatus()
,D/SettingsProvider( 1019): name = Wearable0001
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10098
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10098
,D/GMFPReceiver( 5887): ::::::::Wearable0001::false
,D/SettingsProvider( 1019): name = Wearable0002
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10098
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10098
D/GMFPReceiver( 5887): ::::::::Wearable0002::false
D/GMFPReceiver( 5887): onServiceConnected() : 1
D/GMFPReceiver( 5887): mBluetoothHeadset = true
W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/btif_config_util( 2654): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2654): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2654): Failed to remove device: 7C:F9:0E:37:96:AB
,D/SecContentProvider( 1019): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2654): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 2654): isSecureModeOn:false
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
D/BluetoothTile( 1177):  handleUpdatestate:false name:null,
,D/BluetoothNotiBroadcastReceiver( 1361): onReceive
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,D/HidService( 2654): getHidService(): returning com.android.bluetooth.hid.HidService@339cae18
,D/SettingsProvider( 1019): name = bluetooth_input_device_priority_7C:F9:0E:37:96:AB
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1019): ret = -1
D/HidService( 2654): Saved priority 7C:F9:0E:37:96:AB = -1
,D/SettingsProvider( 1019): name = bluetooth_a2dp_sink_priority_7C:F9:0E:37:96:AB
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,E/BluetoothHeadset( 5887): BTStateChangeCB is registed
,D/SettingsProvider( 1019): name = bluetooth_headset_priority_7C:F9:0E:37:96:AB
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
I/BluetoothBondStateMachine( 2654): StableState(): Entering Off State
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5887): BluetoothHeadset service is binded
D/GMFPReceiver( 5887): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5887): jangil::setProperties()
,D/GMFPReceiver( 5887): jangil::printBTStatus()
,D/SettingsProvider( 1019): name = Wearable0001
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10098
,D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/GMFPReceiver( 5887): ::::::::Wearable0001::false
,D/SettingsProvider( 1019): name = Wearable0002
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
,D/SettingsProvider( 1019): selectionArgs: 10098
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/GMFPReceiver( 5887): ::::::::Wearable0002::false
,D/GMFPReceiver( 5887): onServiceConnected() : 1
D/GMFPReceiver( 5887): mBluetoothHeadset = true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/IOP_DB_BT( 2654): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_VER, value 7:8709
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 2654): db_query_execute: result 1
E/bt-btm  ( 2654): tBTM_SEC_DEV:0xa45c2630 rs_disc_pending=1
,W/bt-btif ( 2654): bta_dm_check_av:0
W/bt-btif ( 2654): btif_dm_cback : unhandled event (14)
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1019): InactiveState{ what=139301 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1019): P2pEnabledState add service request
,D/WifiP2pManager( 6060): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service request added successfully
,D/WifiP2pService( 1019): InactiveState{ what=139310 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,D/WifiService( 1019): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1019): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1019): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1398): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service discovery started successfully,
,D/IOP_DB_BT( 2654): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_VER, value 7:8709
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2654): db_query_execute: result 1
W/bt-btif ( 2654): info:x10
,D/        ( 2654): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 2654): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.NAME_CHANGED
,W/bt-sdp  ( 2654): process_service_search_attr_rsp,
,E/SMD     (  289): DCD OFF
,I/BluetoothBondStateMachine( 2654): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,D/SecContentProvider( 1019): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2654): check_cod: remote_cod = 0x5a020c
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.NAME_CHANGED
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.CLASS_CHANGED
,I/BluetoothBondStateMachine( 2654): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2654): isSecureModeOn:false
I/BluetoothBondStateMachine( 2654): Entering PendingCommandState State
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1361): onReceive,
W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5887): BTStateChangeCB is registed
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
E/BluetoothHeadset( 5887): BluetoothHeadset service is binded
D/GMFPReceiver( 5887): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5887): jangil::setProperties()
,D/GMFPReceiver( 5887): jangil::printBTStatus()
,D/SettingsProvider( 1019): name = Wearable0001
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10098
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/GMFPReceiver( 5887): ::::::::Wearable0001::false
,D/SettingsProvider( 1019): name = Wearable0002
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
,D/SettingsProvider( 1019): selectionArgs: 10098
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,D/GMFPReceiver( 5887): ::::::::Wearable0002::false
,D/GMFPReceiver( 5887): onServiceConnected() : 1
D/GMFPReceiver( 5887): mBluetoothHeadset = true
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/btif_config_util( 2654): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2654): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2654): Failed to remove device: E0:DB:10:14:E2:C0
,D/SecContentProvider( 1019): uri = 4 selection = bluetoothLogForRemote
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,I/BluetoothBondStateMachine( 2654): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 2654): isSecureModeOn:false
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.BOND_STATE_CHANGED
D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/HidService( 2654): getHidService(): returning com.android.bluetooth.hid.HidService@339cae18
,D/SettingsProvider( 1019): name = bluetooth_input_device_priority_E0:DB:10:14:E2:C0
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/HidService( 2654): Saved priority E0:DB:10:14:E2:C0 = -1
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
D/BluetoothNotiBroadcastReceiver( 1361): onReceive
,D/SettingsProvider( 1019): name = bluetooth_a2dp_sink_priority_E0:DB:10:14:E2:C0
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1019): ret = -1
,D/SettingsProvider( 1019): name = bluetooth_headset_priority_E0:DB:10:14:E2:C0
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
I/BluetoothBondStateMachine( 2654): StableState(): Entering Off State
,E/BluetoothHeadset( 5887): BTStateChangeCB is registed
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
E/BluetoothHeadset( 5887): BluetoothHeadset service is binded
,D/GMFPReceiver( 5887): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5887): jangil::setProperties()
,D/GMFPReceiver( 5887): jangil::printBTStatus()
,D/SettingsProvider( 1019): name = Wearable0001
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10098
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/GMFPReceiver( 5887): ::::::::Wearable0001::false
D/SettingsProvider( 1019): name = Wearable0002
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10098
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,D/GMFPReceiver( 5887): ::::::::Wearable0002::false
D/GMFPReceiver( 5887): onServiceConnected() : 1
D/GMFPReceiver( 5887): mBluetoothHeadset = true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,W/bt-btif ( 2654): new conn_srvc id:26, app_id:1,
W/bt-btif ( 2654): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2654): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2654): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): onSocketConnected: [E0:DB:10:14:E2:C0 Note4-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1045)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): onBytesWritten: 63 bytes successfully written (thread ID: 1046)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): Entering thread (ID: 1046)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Outgoing connection initialized (*handshake* thread ID: 1046)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Exiting thread (thread ID: 1045)
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
,D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): onBytesRead: Read 66 bytes successfully (thread ID: 1046),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Handshake succeeded with [E0:DB:10:14:E2:C0 Note4-1],
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): onHandshakeSucceeded: [E0:DB:10:14:E2:C0 Note4-1],
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): Exiting thread (ID: 1046),
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): onConnected: [E0:DB:10:14:E2:C0 Note4-1],
I/io.jxcore.node.ConnectionHelper( 6060): onConnected: Outgoing connection to peer [E0:DB:10:14:E2:C0 Note4-1]
D/io.jxcore.node.ConnectionHelper( 6060): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 Note4-1] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6060): onConnected: Outgoing socket thread, for peer [E0:DB:10:14:E2:C0 Note4-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6060): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 6060): Entering thread (ID: 1047)
,D/io.jxcore.node.OutgoingSocketThread( 6060): Server socket local port: 41460,
I/io.jxcore.node.OutgoingSocketThread( 6060): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 6060): onListeningForIncomingConnections: Outgoing connection is using port 41460 (peer ID: E0:DB:10:14:E2:C0)
,I/jxcore-log( 6060): 2016-01-12T12:23:35.482Z SendDataConnector.js: CLIENT connected to 41460, error: null
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:23:35.483Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6060): 
,I/io.jxcore.node.OutgoingSocketThread( 6060): Incoming data from address: /127.0.0.1, port: 41460
,D/io.jxcore.node.OutgoingSocketThread( 6060): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6060): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6060): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 6060): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6060): Exiting thread (ID: 1047)
,D/io.jxcore.node.StreamCopyingThread( 6060): Entering thread (ID: 1049, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6060): Entering thread (ID: 1048, name: Sender)
,I/jxcore-log( 6060): 2016-01-12T12:23:35.499Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6060): 
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437,
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,D/WifiP2pService( 1019): InactiveState{ what=147494 },
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): Start timer timeout, starting now...,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/WifiP2pService( 1019): InactiveState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/WifiP2pService( 1019): P2pEnabledState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 Nexus 5]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 Nexus 5] already in the list, will not add again
D/WifiService( 1019): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1019): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1019): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1398): USE_NETWORK : USE_NETWORK OFF
,D/        ( 2654): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:30308
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): setState: STARTED
,D/WifiP2pService( 1019): discovery change broadcast true
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 Nexus 5] already in the list, will not add again
,E/SMD     (  289): DCD OFF
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 7E.18.23 p2p_dev_addr=7E.18.23 pri_dev_type=10-0050F204-5  ' A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
D/WifiP2pService( 1019): InactiveState{ what=147477 }
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 },
D/WifiP2pService( 1019): InactiveState{ what=147477 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/WifiDisplayController( 1019): Received list of peers.,
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c,
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80,
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiDisplayController( 1019): Received list of peers.
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,I/jxcore-log( 6060): 2016-01-12T12:23:38.894Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6060): 
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
D/WifiP2pService( 1019): InactiveState{ what=147477 },
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/        ( 2654): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:23088
,I/jxcore-log( 6060): 2016-01-12T12:23:39.958Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6060): 
,E/SMD     (  289): DCD OFF
,I/jxcore-log( 6060): 2016-01-12T12:23:41.123Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6060): 
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 },
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): restart: Restarting...
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): InactiveState{ what=139307 }
D/WifiP2pManager( 6060): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiP2pService( 1019): P2pEnabledState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service request added successfully,
D/WifiP2pService( 1019): P2pEnabledState clear service request
D/WifiP2pService( 1019): InactiveState{ what=139301 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1019): P2pEnabledState add service request
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
,D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,E/SMD     (  289): DCD OFF
,D/WifiP2pService( 1019): InactiveState{ what=139310 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1019): P2pEnabledState discover services
,D/WifiService( 1019): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1019): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1019): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1398): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service discovery started successfully,
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2412,
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
,D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): InactiveState{ what=139283 },
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1019): Received list of peers.
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1019): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/WifiP2pService( 1019): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,W/bt-btif ( 2654): dm_pm_timer expires
,W/bt-btif ( 2654): dm_pm_timer expires 0
W/bt-btif ( 2654): proc dm_pm_timer expires
,E/SMD     (  289): DCD OFF
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1],
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,I/Atfwd_Daemon(  315): Stop the daemon....,
,E/SMD     (  289): DCD OFF
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 },
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,I/jxcore-log( 6060): 2016-01-12T12:23:51.645Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:23:51.877Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6060): 
,E/SMD     (  289): DCD OFF
,I/jxcore-log( 6060): 2016-01-12T12:23:52.809Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:23:53.599Z SendDataConnector.js: CLIENT is data received : 80000,
I/jxcore-log( 6060): 
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 },
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered,
D/WifiP2pService( 1019): DefaultState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1019): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1019): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c,
D/WifiP2pService( 1019): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019): InactiveState{ what=139301 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1019): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): restart: Restarting...
D/WifiP2pManager( 6060): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service request added successfully
,E/Watchdog( 1019): !@Sync 19,
,D/WifiP2pService( 1019): InactiveState{ what=139310 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1019): P2pEnabledState discover services
,D/WifiService( 1019): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1019): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1019): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1398): USE_NETWORK : USE_NETWORK OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service discovery started successfully
,I/jxcore-log( 6060): 2016-01-12T12:23:55.110Z SendDataConnector.js: CLIENT is data received : 90000,
I/jxcore-log( 6060): 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/bt-btm  ( 2654): tBTM_SEC_DEV:0xa45c2630 rs_disc_pending=1
,E/bt-btm  ( 2654): Reset sec_bd_name and name flag. (BR/EDR link)
E/bt-btm  ( 2654): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2654): bta_dm_check_av:0
W/bt-btif ( 2654): btif_dm_cback : unhandled event (14)
,D/IOP_DB_BT( 2654): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 2654): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2654): db_query_execute: result 1
,D/KeyguardViewMediator( 1177): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive,
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1361): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/KeyguardViewMediator( 1177): isGear1: device is not B1!
,D/BluetoothAdapterService( 2654): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35e3bb96
,D/BtConfig.SecureMode( 2654): isSecureModeOn:false
,D/SecContentProvider( 1019): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2654): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5936): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5936): Bluetooth Device Name: A5-1
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/IOP_DB_BT( 2654): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2654): db_query_execute: result 1
W/bt-btif ( 2654): info:x10
D/        ( 2654): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2654): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 6060): 2016-01-12T12:23:56.093Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:23:56.094Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): oneRoundDownNow
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:23:56.097Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:23:56.098Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6060): 
,D/io.jxcore.node.ConnectionHelper( 6060): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
,I/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 6060): close
D/io.jxcore.node.OutgoingSocketThread( 6060): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 6060): doStop: Thread ID: 1049
D/io.jxcore.node.OutgoingSocketThread( 6060): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6060): doStop: Thread ID: 1048
D/io.jxcore.node.OutgoingSocketThread( 6060): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6060): closeLocalSocketAndStreams: Closing the local input stream...
,D/io.jxcore.node.OutgoingSocketThread( 6060): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6060): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6060): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@39aa431e, channel: 6, state: CONNECTED
D/BluetoothSocket( 6060): close() this: android.bluetooth.BluetoothSocket@39aa431e, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3525e7ff, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c0da9ccmSocket: android.net.LocalSocket@3b55a415 impl:android.net.LocalSocketImpl@18b3732a fd:FileDescriptor[111]
D/BluetoothSocket( 6060): Closing mSocket: android.net.LocalSocket@3b55a415 impl:android.net.LocalSocketImpl@18b3732a fd:FileDescriptor[111]
,W/io.jxcore.node.StreamCopyingThread( 6060): Either failed to read from the output stream or write to the input stream (thread ID: 1049, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6060): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6060): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 Note4-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.StreamCopyingThread( 6060): Either failed to read from the output stream or write to the input stream (thread ID: 1048, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6060): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6060): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 Note4-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@39aa431e, channel: 6, state: CLOSED
D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@39aa431e, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6060): disconnectOutgoingConnection: Successfully disconnected (peer ID: E0:DB:10:14:E2:C0
,E/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6060): Exiting thread (ID: 1049, name: Receiver)
I/jxcore-log( 6060): 2016-01-12T12:23:56.108Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6060): 
E/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
,D/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6060): Exiting thread (ID: 1048, name: Sender)
I/jxcore-log( 6060): ---- round done--------
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): startWithNextDevice
I/jxcore-log( 6060): 
I/jxcore-log( 6060): do fake peer & start
I/jxcore-log( 6060): 
I/jxcore-log( 6060): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:23:56.111Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:23:56.112Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:23:56.112Z SendDataConnector.js: do connect now
I/jxcore-log( 6060): 
,I/io.jxcore.node.ConnectionHelper( 6060): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
,D/io.jxcore.node.ConnectionHelper( 6060): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): connect: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 6060): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 1050)
,D/BluetoothUtils( 6060): isSocketAllowedBySecurityPolicy start : device null
W/BluetoothAdapter( 6060): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2654): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 2654): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_DIR_ALL, value 1
D/BluetoothSocket( 6060): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
D/IOP_DB_BT( 2654): db_query_execute: result 1
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.NAME_CHANGED
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [44:80:EB:7B:5A:05 XT1072]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 XT1072]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 XT1072] already in the list, will not add again
,E/SMD     (  289): DCD OFF
,D/WifiP2pService( 1019): InactiveState{ what=147494 },
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,W/bt-btif ( 2654): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,V/AlarmManager( 1019): waitForAlarm result :8
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 2654): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.CLASS_CHANGED
D/SecContentProvider( 1019): uri = 4 selection = bluetoothLogForRemote
I/BluetoothBondStateMachine( 2654): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
E/bt-btif ( 2654): check_cod: remote_cod = 0x5a020c
,D/BtConfig.SecureMode( 2654): isSecureModeOn:false
I/BluetoothBondStateMachine( 2654): Entering PendingCommandState State
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10,
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/BluetoothTile( 1177):  handleUpdatestate:false name:null
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1361): onReceive
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5887): BTStateChangeCB is registed
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5887): BluetoothHeadset service is binded
D/GMFPReceiver( 5887): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5887): jangil::setProperties()
,D/GMFPReceiver( 5887): jangil::printBTStatus()
,D/SettingsProvider( 1019): name = Wearable0001
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10098
,D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,D/GMFPReceiver( 5887): ::::::::Wearable0001::false
,D/SettingsProvider( 1019): name = Wearable0002
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10098
,D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1019): ret = -1
,D/GMFPReceiver( 5887): ::::::::Wearable0002::false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/GMFPReceiver( 5887): onServiceConnected() : 1
,D/GMFPReceiver( 5887): mBluetoothHeadset = true
,E/SMD     (  289): DCD OFF
,D/btif_config_util( 2654): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2654): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2654): Failed to remove device: B0:C5:59:3F:75:69
,D/SecContentProvider( 1019): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2654): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2654): isSecureModeOn:false
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
D/HidService( 2654): getHidService(): returning com.android.bluetooth.hid.HidService@339cae18
,D/SettingsProvider( 1019): name = bluetooth_input_device_priority_B0:C5:59:3F:75:69
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings,
,D/HidService( 2654): Saved priority B0:C5:59:3F:75:69 = -1
D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1361): onReceive
,D/SettingsProvider( 1019): name = bluetooth_a2dp_sink_priority_B0:C5:59:3F:75:69
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
D/SettingsProvider( 1019): ret = -1
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,D/SettingsProvider( 1019): name = bluetooth_headset_priority_B0:C5:59:3F:75:69
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,I/BluetoothBondStateMachine( 2654): StableState(): Entering Off State
,E/BluetoothHeadset( 5887): BTStateChangeCB is registed
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5887): BluetoothHeadset service is binded
D/GMFPReceiver( 5887): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5887): jangil::setProperties()
,D/GMFPReceiver( 5887): jangil::printBTStatus(),
D/SettingsProvider( 1019): name = Wearable0001
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
,D/SettingsProvider( 1019): selectionArgs: 10098
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/GMFPReceiver( 5887): ::::::::Wearable0001::false
D/SettingsProvider( 1019): name = Wearable0002
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
,D/SettingsProvider( 1019): selectionArgs: 10098
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1019): ret = -1
,D/GMFPReceiver( 5887): ::::::::Wearable0002::false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/GMFPReceiver( 5887): onServiceConnected() : 1
D/GMFPReceiver( 5887): mBluetoothHeadset = true
,W/bt-btif ( 2654): new conn_srvc id:26, app_id:255
,D/BluetoothSocket( 6060): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@2dfb051b
,W/bt-btif ( 2654): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2654): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2654): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Incoming connection initialized (thread ID: 1051)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): Entering thread (ID: 1051)
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/bt-btif ( 2654): invalid rfc slot id: 5
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): Disconnected: bt socket closed, read return: -1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): removeThreadFromList: Removing thread with ID 1051
D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@1d5196b8, channel: 6, state: CONNECTED
D/BluetoothSocket( 6060): close() this: android.bluetooth.BluetoothSocket@1d5196b8, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21f96c91, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3f6d97f6mSocket: android.net.LocalSocket@243ad7f7 impl:android.net.LocalSocketImpl@1ae56664 fd:FileDescriptor[109]
D/BluetoothSocket( 6060): Closing mSocket: android.net.LocalSocket@243ad7f7 impl:android.net.LocalSocketImpl@1ae56664 fd:FileDescriptor[109]
D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@1d5196b8, channel: 6, state: CLOSED
D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@1d5196b8, channel: 6, state: CLOSED
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Handshake failed (thread ID: 1051)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): Exiting thread (ID: 1051)
,W/bt-rfcomm( 2654): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
,W/bt-rfcomm( 2654): RFCOMM_DisconnectInd LCID:0x47
,E/bt-btm  ( 2654): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2654): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1177): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1361): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/KeyguardViewMediator( 1177): isGear1: device is not B1!
,D/BluetoothAdapterService( 2654): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35e3bb96
D/BtConfig.SecureMode( 2654): isSecureModeOn:false
,D/SecContentProvider( 1019): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2654): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5936): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5936): Bluetooth Device Name: Note4-1
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 },
D/WifiP2pService( 1019): InactiveState{ what=147477 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Rec,eived list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pService( 1019): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1019): P2pEnabledState clear service request
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): restart: Restarting...
,D/WifiP2pService( 1019): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072],
D/WifiP2pService( 1019): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1019): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/WifiP2pManager( 6060): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service request added successfully
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1019): stay LED for fully charged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/WifiP2pService( 1019): InactiveState{ what=139310 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1019): P2pEnabledState discover services
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/WifiStateMachine( 1019): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1019): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1019): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1398): USE_NETWORK : USE_NETWORK OFF
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service discovery started successfully
D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/bt-btm  ( 2654): Reset sec_bd_name and name flag. (BR/EDR link),
E/bt-btm  ( 2654): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1177): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.ACL_DISCONNECTED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,E/BluetoothEventManager( 1361): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 1177): isGear1: device is not B1!
,D/BluetoothAdapterService( 2654): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35e3bb96
,D/BtConfig.SecureMode( 2654): isSecureModeOn:false
,D/SecContentProvider( 1019): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2654): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5936): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5936): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
,I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)],
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,E/SMD     (  289): DCD OFF
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1019): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
,D/WifiP2pService( 1019): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 Note4-1] already in the list, will not add again
,I/PowerManagerService( 1019): [PWL] Off : 525s ago
,I/PowerManagerService( 1019): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1019): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1019): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=2654, ws=null) (elapsedTime=38795)
,E/SMD     (  289): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): onConnectionTimeout: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437,
I/jxcore-log( 6060): 2016-01-12T12:24:11.122Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] timed out
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:24:11.123Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] timed out
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:24:11.123Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6060): 
,D/WifiP2pService( 1019): InactiveState{ what=147477 },
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.,
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
,D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pService( 1019): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log( 6060): 2016-01-12T12:24:16.124Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:16.125Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6060): 
,E/SMD     (  289): DCD OFF
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
D/WifiP2pService( 1019): InactiveState{ what=147477 },
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1019): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1019): P2pEnabledState{ what=139307 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
,D/WifiP2pService( 1019): P2pEnabledState clear service request,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/WifiP2pService( 1019): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019): P2pEnabledState{ what=139301 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1019): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): restart: Restarting...
D/WifiP2pManager( 6060): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service request added successfully
,E/SMD     (  289): DCD OFF
,D/WifiP2pService( 1019): InactiveState{ what=139310 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,D/WifiService( 1019): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1019): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiStateMachine( 1019): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1398): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service discovery started successfully
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 Note4-1] already in the list, will not add again
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,D/io.jxcore.node.ConnectionHelper( 6060): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6060): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 6060): 2016-01-12T12:24:21.127Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:24:21.128Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:24:21.128Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:21.128Z SendDataConnector.js: do connect now
I/jxcore-log( 6060): 
I/io.jxcore.node.ConnectionHelper( 6060): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6060): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): connect: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): onConnecting: null 08:EC:A9:50:76:27
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): connect: Started connecting to null in address 08:EC:A9:50:76:27
,I/io.jxcore.node.ConnectionHelper( 6060): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 1053)
,D/BluetoothUtils( 6060): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 6060): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2654): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 6060): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [34:FC:EF:11:AE:67 Nexus 5], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 Nexus 5] already in the list, will not add again
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"XT1072","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [44:80:EB:7B:5A:05 XT1072]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 XT1072]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [44:80:EB:7B:5A:05 XT1072], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 XT1072] already in the list, will not add again
,E/Watchdog( 1019): !@Sync 20
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,W/bt-sdp  ( 2654): SDP - Rcvd conn cnf with error: 0x8  CID 0x44
,E/bt-btif ( 2654): DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
D/IOP_DB_BT( 2654): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
W/bt-btif ( 2654): invalid rfc slot id: 7
,D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 2654): db_query_execute: result 1
,D/IOP_DB_BT( 2654): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 2654): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2654): db_query_execute: result 1
,D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@2e3740cd, channel: -1, state: INIT
D/BluetoothSocket( 6060): close() this: android.bluetooth.BluetoothSocket@2e3740cd, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ed33d82, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@213afc93mSocket: android.net.LocalSocket@bc484d0 impl:android.net.LocalSocketImpl@2c041cc9 fd:FileDescriptor[111]
D/BluetoothSocket( 6060): Closing mSocket: android.net.LocalSocket@bc484d0 impl:android.net.LocalSocketImpl@2c041cc9 fd:FileDescriptor[111]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 1050)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): shutdown (thread ID: 1050)
D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@2e3740cd, channel: -1, state: CLOSED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Maximum number of allowed retries (0) reached, giving up... (thread ID: 1050)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Exiting thread (thread ID: 1050)
,I/jxcore-log( 6060): 2016-01-12T12:24:29.778Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] failed
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:24:29.778Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] failed
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:29.779Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6060): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/IOP_DB_BT( 2654): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2654): db_query_execute: result 1
,W/bt-btif ( 2654): info:x10
,D/        ( 2654): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,D/KeyguardViewMediator( 1177): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_ACL_CONNECTED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1361): onReceive
,D/KeyguardViewMediator( 1177): isGear1: device is not B1!
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.NAME_CHANGED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5936): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5936): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,W/bt-btif ( 2654): new conn_srvc id:26, app_id:255,
W/bt-btif ( 2654): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2654): bta_dm_pm_ssr:2, lat:1200
D/BluetoothSocket( 6060): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@afbafce
E/BluetoothRemoteDevices( 2654): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Incoming connection initialized (thread ID: 1055)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): Entering thread (ID: 1055)
,W/bt-btif ( 2654): invalid rfc slot id: 8
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): Disconnected: bt socket closed, read return: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): removeThreadFromList: Removing thread with ID 1055
,D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@240eceef, channel: 6, state: CONNECTED
D/BluetoothSocket( 6060): close() this: android.bluetooth.BluetoothSocket@240eceef, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@19351dfc, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@17a8bc85mSocket: android.net.LocalSocket@1026fada impl:android.net.LocalSocketImpl@1fa36b0b fd:FileDescriptor[109]
,D/BluetoothSocket( 6060): Closing mSocket: android.net.LocalSocket@1026fada impl:android.net.LocalSocketImpl@1fa36b0b fd:FileDescriptor[109]
D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@240eceef, channel: 6, state: CLOSED
,D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@240eceef, channel: 6, state: CLOSED
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Handshake failed (thread ID: 1055)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): Exiting thread (ID: 1055)
,W/bt-rfcomm( 2654): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
,W/bt-rfcomm( 2654): RFCOMM_DisconnectInd LCID:0x4a
,E/SMD     (  289): DCD OFF
,I/jxcore-log( 6060): 2016-01-12T12:24:34.779Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:34.780Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6060): 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/btif_config_util( 2654): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/SMD     (  289): DCD OFF
,W/bt-btif ( 2654): new conn_srvc id:26, app_id:255
,D/BluetoothSocket( 6060): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@18b41de8
W/bt-btif ( 2654): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2654): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2654): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Incoming connection initialized (thread ID: 1056)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): Entering thread (ID: 1056)
,D/io.jxcore.node.ConnectionHelper( 6060): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
,E/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6060): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
,I/jxcore-log( 6060): 2016-01-12T12:24:39.783Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:24:39.784Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:39.785Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:24:39.785Z SendDataConnector.js: do connect now
I/jxcore-log( 6060): 
,I/io.jxcore.node.ConnectionHelper( 6060): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
,D/io.jxcore.node.ConnectionHelper( 6060): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): connect: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): onConnecting: null 08:EC:A9:50:76:27
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 6060): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 1057)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6060): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 6060): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2654): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 6060): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[113]}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): onBytesRead: Read 81 bytes successfully (thread ID: 1056)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Got valid identity from [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): onBytesWritten: 63 bytes successfully written (thread ID: 1056)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): removeThreadFromList: Removing thread with ID 1056
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Handshake thread disposed (thread ID: 1056)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): onConnected: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 6060): onConnected: Incoming connection to peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/io.jxcore.node.ConnectionHelper( 6060): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
,W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6060): onConnected: Incoming socket thread, for peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], created successfully
,D/io.jxcore.node.ConnectionHelper( 6060): onConnected: The total number of connections is now 1
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): Exiting thread (ID: 1056)
,D/io.jxcore.node.IncomingSocketThread( 6060): Entering thread (ID: 1058)
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10338
,I/io.jxcore.node.IncomingSocketThread( 6060): Local host address: localhost/127.0.0.1, port: 36121
,I/jxcore-log( 6060): 2016-01-12T12:24:39.982Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6060): 
,D/io.jxcore.node.IncomingSocketThread( 6060): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6060): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6060): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 6060): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6060): Exiting thread (ID: 1058)
,D/io.jxcore.node.StreamCopyingThread( 6060): Entering thread (ID: 1060, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6060): Entering thread (ID: 1059, name: Sender)
,D/IOP_DB_BT( 2654): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_VER, value 0:0
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2654): db_query_execute: result 1
,D/IOP_DB_BT( 2654): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_VER, value 7:8709
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2654): db_query_execute: result 1
,W/bt-btif ( 2654): info:x10
D/        ( 2654): remote version info [08:ec:a9:50:76:27]: 7, f, 2205
,E/BluetoothRemoteDevices( 2654): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.NAME_CHANGED
,W/bt-sdp  ( 2654): process_service_search_attr_rsp
,W/bt-sdp  ( 2654): process_service_search_attr_rsp
,E/bt-rfcomm( 2654): RFCOMM_CreateConnection - already opened state:1, RFC state:0, MCB state:1
,E/bt-btif ( 2654): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
W/bt-btif ( 2654): invalid rfc slot id: 12
,D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@2f3d9c01, channel: 6, state: INIT
D/BluetoothSocket( 6060): close() this: android.bluetooth.BluetoothSocket@2f3d9c01, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c89eaa6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3e9bace7mSocket: android.net.LocalSocket@38a13094 impl:android.net.LocalSocketImpl@1fe6f73d fd:FileDescriptor[113]
D/BluetoothSocket( 6060): Closing mSocket: android.net.LocalSocket@38a13094 impl:android.net.LocalSocketImpl@1fe6f73d fd:FileDescriptor[113]
,D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@2f3d9c01, channel: 6, state: CLOSED
,D/BluetoothUtils( 6060): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 6060): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2654): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/BluetoothSocket( 6060): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[115]}
,W/bt-sdp  ( 2654): process_service_search_attr_rsp
,E/bt-rfcomm( 2654): RFCOMM_CreateConnection - already opened state:1, RFC state:0, MCB state:1
,E/bt-btif ( 2654): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
W/bt-btif ( 2654): invalid rfc slot id: 13
D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@2ada0b32, channel: 6, state: INIT
D/BluetoothSocket( 6060): close() this: android.bluetooth.BluetoothSocket@2ada0b32, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@8ec3083, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@baac200mSocket: android.net.LocalSocket@ad0ca39 impl:android.net.LocalSocketImpl@1999a87e fd:FileDescriptor[115]
D/BluetoothSocket( 6060): Closing mSocket: android.net.LocalSocket@ad0ca39 impl:android.net.LocalSocketImpl@1999a87e fd:FileDescriptor[115]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 1057)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Maximum number of allowed retries (0) reached, giving up... (thread ID: 1057)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Exiting thread (thread ID: 1057)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/jxcore-log( 6060): 2016-01-12T12:24:40.199Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] failed
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:24:40.199Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] failed
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:24:40.200Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6060): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): shutdown (thread ID: 1057)
D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@2ada0b32, channel: 6, state: CLOSED
,D/IOP_DB_BT( 2654): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_VER, value 0:0
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2654): db_query_execute: result 1
,W/bt-btif ( 2654): info:x10
,D/        ( 2654): remote version info [7c:f9:0e:37:96:ab]: 0, 0, 0
,D/KeyguardViewMediator( 1177): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_ACL_CONNECTED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1361): onReceive
,D/KeyguardViewMediator( 1177): isGear1: device is not B1!
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5936): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5936): Bluetooth Device Name: A5-1
,E/SMD     (  289): DCD OFF
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.NAME_CHANGED
,W/bt-btif ( 2654): new conn_srvc id:26, app_id:255
,D/BluetoothSocket( 6060): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@73751df
W/bt-btif ( 2654): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2654): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2654): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Incoming connection initialized (thread ID: 1062)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): Entering thread (ID: 1062)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): onBytesRead: Read 63 bytes successfully (thread ID: 1062)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Got valid identity from [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): onBytesWritten: 63 bytes successfully written (thread ID: 1062)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): removeThreadFromList: Removing thread with ID 1062
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Handshake thread disposed (thread ID: 1062)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB A5-1]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): onConnected: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 6060): onConnected: Incoming connection to peer [7C:F9:0E:37:96:AB A5-1]
D/io.jxcore.node.ConnectionHelper( 6060): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
,W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): Exiting thread (ID: 1062)
,I/io.jxcore.node.ConnectionHelper( 6060): onConnected: Incoming socket thread, for peer [7C:F9:0E:37:96:AB A5-1], created successfully
,D/io.jxcore.node.ConnectionHelper( 6060): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 6060): Entering thread (ID: 1063)
,I/io.jxcore.node.IncomingSocketThread( 6060): Local host address: localhost/127.0.0.1, port: 36121
,D/io.jxcore.node.IncomingSocketThread( 6060): Setting local streams and starting stream copying threads...
,I/jxcore-log( 6060): 2016-01-12T12:24:40.896Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6060): 
,I/io.jxcore.node.StreamCopyingThread( 6060): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6060): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 6060): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6060): Exiting thread (ID: 1063)
,D/io.jxcore.node.StreamCopyingThread( 6060): Entering thread (ID: 1065, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6060): Entering thread (ID: 1064, name: Sender)
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 2654): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,D/SecContentProvider( 1019): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2654): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 2654): isSecureModeOn:false
,I/BluetoothBondStateMachine( 2654): Entering PendingCommandState State
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,E/bt-btif ( 2654): check_cod: remote_cod = 0x5a020c,
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive
V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.CLASS_CHANGED
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/BluetoothTile( 1177):  handleUpdatestate:false name:null
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11,
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1361): onReceive
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5887): BTStateChangeCB is registed
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5887): BluetoothHeadset service is binded
D/GMFPReceiver( 5887): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5887): jangil::setProperties()
,D/GMFPReceiver( 5887): jangil::printBTStatus()
,D/SettingsProvider( 1019): name = Wearable0001
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10098
,D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/GMFPReceiver( 5887): ::::::::Wearable0001::false
,D/SettingsProvider( 1019): name = Wearable0002
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10098
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,D/GMFPReceiver( 5887): ::::::::Wearable0002::false
,D/GMFPReceiver( 5887): onServiceConnected() : 1,
D/GMFPReceiver( 5887): mBluetoothHeadset = true
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/btif_config_util( 2654): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2654): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2654): Failed to remove device: 08:EC:A9:50:76:27
D/SecContentProvider( 1019): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2654): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2654): isSecureModeOn:false
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/HidService( 2654): getHidService(): returning com.android.bluetooth.hid.HidService@339cae18
D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,D/SettingsProvider( 1019): name = bluetooth_input_device_priority_08:EC:A9:50:76:27
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.BOND_STATE_CHANGED
D/HidService( 2654): Saved priority 08:EC:A9:50:76:27 = -1
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/SettingsProvider( 1019): name = bluetooth_a2dp_sink_priority_08:EC:A9:50:76:27,
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1019): ret = -1
D/SettingsProvider( 1019): name = bluetooth_headset_priority_08:EC:A9:50:76:27
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
,D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/BluetoothNotiBroadcastReceiver( 1361): onReceive
,I/BluetoothBondStateMachine( 2654): StableState(): Entering Off State
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5887): BTStateChangeCB is registed
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5887): BluetoothHeadset service is binded
,D/GMFPReceiver( 5887): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5887): jangil::setProperties()
,D/GMFPReceiver( 5887): jangil::printBTStatus()
,D/SettingsProvider( 1019): name = Wearable0001
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
,D/SettingsProvider( 1019): selectionArgs: 10098
,D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,D/GMFPReceiver( 5887): ::::::::Wearable0001::false
,D/SettingsProvider( 1019): name = Wearable0002
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10098
,D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,D/GMFPReceiver( 5887): ::::::::Wearable0002::false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/GMFPReceiver( 5887): onServiceConnected() : 1
D/GMFPReceiver( 5887): mBluetoothHeadset = true
,E/bt-btm  ( 2654): tBTM_SEC_DEV:0xa45c2b7c rs_disc_pending=1
,W/bt-btif ( 2654): bta_dm_check_av:0
W/bt-btif ( 2654): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6060): 2016-01-12T12:24:41.588Z SendDataTCPServer.js: TCP/IP server has received 1012 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.651Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.661Z SendDataTCPServer.js: TCP/IP server has received 3036 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.665Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.670Z SendDataTCPServer.js: TCP/IP server has received 5060 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.676Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.683Z SendDataTCPServer.js: TCP/IP server has received 7084 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.687Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.690Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.696Z SendDataTCPServer.js: TCP/IP server has received 9204 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.702Z SendDataTCPServer.js: TCP/IP server has received 10216 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.712Z SendDataTCPServer.js: TCP/IP server has received 11228 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.745Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data,
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.747Z SendDataTCPServer.js: TCP/IP server has received 17396 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.750Z SendDataTCPServer.js: TCP/IP server has received 18408 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.756Z SendDataTCPServer.js: TCP/IP server has received 19420 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.797Z SendDataTCPServer.js: TCP/IP server has received 20432 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.803Z SendDataTCPServer.js: TCP/IP server has received 21444 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.836Z SendDataTCPServer.js: TCP/IP server has received 23468 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.839Z SendDataTCPServer.js: TCP/IP server has received 24480 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.845Z SendDataTCPServer.js: TCP/IP server has received 25492 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.852Z SendDataTCPServer.js: TCP/IP server has received 26504 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.864Z SendDataTCPServer.js: TCP/IP server has received 27516 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.870Z SendDataTCPServer.js: TCP/IP server has received 28528 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.877Z SendDataTCPServer.js: TCP/IP server has received 29540 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.881Z SendDataTCPServer.js: TCP/IP server has received 30552 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.886Z SendDataTCPServer.js: TCP/IP server has received 31564 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.925Z SendDataTCPServer.js: TCP/IP server has received 37636 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.948Z SendDataTCPServer.js: TCP/IP server has received 38648 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.959Z SendDataTCPServer.js: TCP/IP server has received 39660 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.964Z SendDataTCPServer.js: TCP/IP server has received 40672 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:41.969Z SendDataTCPServer.js: TCP/IP server has received 41684 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.006Z SendDataTCPServer.js: TCP/IP server has received 46744 bytes of data,
I/jxcore-log( 6060): 
,W/bt-btif ( 2654): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2654): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2654): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2654): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): onSocketConnected: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): shutdown (thread ID: 1053)
,D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@1ef9fe2c, channel: 6, state: CONNECTED
D/BluetoothSocket( 6060): close() this: android.bluetooth.BluetoothSocket@1ef9fe2c, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1dead0f5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1b23ce8amSocket: android.net.LocalSocket@3fe92cfb impl:android.net.LocalSocketImpl@71ed118 fd:FileDescriptor[112]
,D/BluetoothSocket( 6060): Closing mSocket: android.net.LocalSocket@3fe92cfb impl:android.net.LocalSocketImpl@71ed118 fd:FileDescriptor[112]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1053)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Exiting thread (thread ID: 1053)
,I/jxcore-log( 6060): 2016-01-12T12:24:42.047Z SendDataTCPServer.js: TCP/IP server has received 48768 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.050Z SendDataTCPServer.js: TCP/IP server has received 49780 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.064Z SendDataTCPServer.js: TCP/IP server has received 50792 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.104Z SendDataTCPServer.js: TCP/IP server has received 51804 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.108Z SendDataTCPServer.js: TCP/IP server has received 1012 bytes of data
I/jxcore-log( 6060): 
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.123Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.136Z SendDataTCPServer.js: TCP/IP server has received 54840 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.140Z SendDataTCPServer.js: TCP/IP server has received 3036 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.176Z SendDataTCPServer.js: TCP/IP server has received 58888 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.199Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.216Z SendDataTCPServer.js: TCP/IP server has received 62936 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.220Z SendDataTCPServer.js: TCP/IP server has received 5060 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.272Z SendDataTCPServer.js: TCP/IP server has received 63948 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.275Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.300Z SendDataTCPServer.js: TCP/IP server has received 7084 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.305Z SendDataTCPServer.js: TCP/IP server has received 66984 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.308Z SendDataTCPServer.js: TCP/IP server has received 67996 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.313Z SendDataTCPServer.js: TCP/IP server has received 69008 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.345Z SendDataTCPServer.js: TCP/IP server has received 73056 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.349Z SendDataTCPServer.js: TCP/IP server has received 74068 bytes of data
I/jxcore-log( 6060): 
,E/bt-btm  ( 2654): tBTM_SEC_DEV:0xa45c2b7c rs_disc_pending=0
,W/bt-btif ( 2654): bta_dm_check_av:0
W/bt-btif ( 2654): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6060): 2016-01-12T12:24:42.407Z SendDataTCPServer.js: TCP/IP server has received 75080 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.446Z SendDataTCPServer.js: TCP/IP server has received 82164 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.455Z SendDataTCPServer.js: TCP/IP server has received 83176 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.459Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.495Z SendDataTCPServer.js: TCP/IP server has received 89248 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.514Z SendDataTCPServer.js: TCP/IP server has received 90260 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.519Z SendDataTCPServer.js: TCP/IP server has received 91272 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.555Z SendDataTCPServer.js: TCP/IP server has received 92284 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.566Z SendDataTCPServer.js: TCP/IP server has received 9108 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.595Z SendDataTCPServer.js: TCP/IP server has received 98356 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.609Z SendDataTCPServer.js: TCP/IP server has received 10120 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.618Z SendDataTCPServer.js: TCP/IP server has received 11132 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.635Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:42.655Z SendDataTCPServer.js: TCP/IP server has received 12144 bytes of data
I/jxcore-log( 6060): 
,W/bt-btif ( 2654): invalid rfc slot id: 10
,W/io.jxcore.node.StreamCopyingThread( 6060): Either failed to read from the output stream or write to the input stream (thread ID: 1060, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6060): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 6060): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1058
,D/io.jxcore.node.IncomingSocketThread( 6060): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6060): doStop: Thread ID: 1060
D/io.jxcore.node.IncomingSocketThread( 6060): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 6060): doStop: Thread ID: 1059
W/bt-btif ( 2654): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,D/io.jxcore.node.IncomingSocketThread( 6060): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6060): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6060): Either failed to read from the output stream or write to the input stream (thread ID: 1059, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6060): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6060): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 6060): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6060): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6060): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@3c648771, channel: 6, state: CONNECTED
D/BluetoothSocket( 6060): close() this: android.bluetooth.BluetoothSocket@3c648771, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a784956, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a139dd7mSocket: android.net.LocalSocket@fbbe6c4 impl:android.net.LocalSocketImpl@32e929ad fd:FileDescriptor[109]
D/BluetoothSocket( 6060): Closing mSocket: android.net.LocalSocket@fbbe6c4 impl:android.net.LocalSocketImpl@32e929ad fd:FileDescriptor[109]
D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@3c648771, channel: 6, state: CLOSED
I/jxcore-log( 6060): 2016-01-12T12:24:42.717Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6060): 
D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@3c648771, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6060): Exiting thread (ID: 1060, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6060): Exiting thread (ID: 1059, name: Sender)
,I/jxcore-log( 6060): 2016-01-12T12:24:43.019Z SendDataTCPServer.js: TCP/IP server has received 13156 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.043Z SendDataTCPServer.js: TCP/IP server has received 14168 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.054Z SendDataTCPServer.js: TCP/IP server has received 15180 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.072Z SendDataTCPServer.js: TCP/IP server has received 16192 bytes of data,
I/jxcore-log( 6060): 
,E/bt-btm  ( 2654): tBTM_SEC_DEV:0xa45c2b7c rs_disc_pending=1
,W/bt-btif ( 2654): bta_dm_check_av:0
W/bt-btif ( 2654): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6060): 2016-01-12T12:24:43.085Z SendDataTCPServer.js: TCP/IP server has received 17204 bytes of data
I/jxcore-log( 6060): 
,E/bt-btm  ( 2654): tBTM_SEC_DEV:0xa45c29b8 rs_disc_pending=0
,W/bt-btif ( 2654): bta_dm_check_av:0
W/bt-btif ( 2654): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6060): 2016-01-12T12:24:43.246Z SendDataTCPServer.js: TCP/IP server has received 18216 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.255Z SendDataTCPServer.js: TCP/IP server has received 19228 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.269Z SendDataTCPServer.js: TCP/IP server has received 20240 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.276Z SendDataTCPServer.js: TCP/IP server has received 21252 bytes of data
I/jxcore-log( 6060): 
,E/SMD     (  289): DCD OFF
,I/jxcore-log( 6060): 2016-01-12T12:24:43.351Z SendDataTCPServer.js: TCP/IP server has received 22264 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.420Z SendDataTCPServer.js: TCP/IP server has received 23276 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.426Z SendDataTCPServer.js: TCP/IP server has received 24288 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.439Z SendDataTCPServer.js: TCP/IP server has received 25300 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.480Z SendDataTCPServer.js: TCP/IP server has received 26312 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.491Z SendDataTCPServer.js: TCP/IP server has received 27324 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.497Z SendDataTCPServer.js: TCP/IP server has received 28336 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.504Z SendDataTCPServer.js: TCP/IP server has received 29348 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.516Z SendDataTCPServer.js: TCP/IP server has received 30360 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.521Z SendDataTCPServer.js: TCP/IP server has received 31372 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.584Z SendDataTCPServer.js: TCP/IP server has received 32384 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.629Z SendDataTCPServer.js: TCP/IP server has received 33396 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.636Z SendDataTCPServer.js: TCP/IP server has received 34408 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.645Z SendDataTCPServer.js: TCP/IP server has received 35420 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.657Z SendDataTCPServer.js: TCP/IP server has received 36432 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.676Z SendDataTCPServer.js: TCP/IP server has received 37444 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.787Z SendDataTCPServer.js: TCP/IP server has received 38456 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.800Z SendDataTCPServer.js: TCP/IP server has received 39468 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.806Z SendDataTCPServer.js: TCP/IP server has received 40480 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.814Z SendDataTCPServer.js: TCP/IP server has received 41492 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.846Z SendDataTCPServer.js: TCP/IP server has received 44528 bytes of data
I/jxcore-log( 6060): 
,W/bt-rfcomm( 2654): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
,W/bt-rfcomm( 2654): RFCOMM_DisconnectInd LCID:0x4c
,I/jxcore-log( 6060): 2016-01-12T12:24:43.938Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.954Z SendDataTCPServer.js: TCP/IP server has received 46552 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.967Z SendDataTCPServer.js: TCP/IP server has received 47564 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.977Z SendDataTCPServer.js: TCP/IP server has received 48576 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.990Z SendDataTCPServer.js: TCP/IP server has received 49588 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:43.996Z SendDataTCPServer.js: TCP/IP server has received 50600 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.036Z SendDataTCPServer.js: TCP/IP server has received 51612 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.075Z SendDataTCPServer.js: TCP/IP server has received 52624 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.090Z SendDataTCPServer.js: TCP/IP server has received 53636 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.099Z SendDataTCPServer.js: TCP/IP server has received 54648 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.111Z SendDataTCPServer.js: TCP/IP server has received 55660 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.118Z SendDataTCPServer.js: TCP/IP server has received 56672 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.130Z SendDataTCPServer.js: TCP/IP server has received 57684 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.140Z SendDataTCPServer.js: TCP/IP server has received 58696 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.146Z SendDataTCPServer.js: TCP/IP server has received 59708 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.186Z SendDataTCPServer.js: TCP/IP server has received 60720 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.194Z SendDataTCPServer.js: TCP/IP server has received 61732 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.225Z SendDataTCPServer.js: TCP/IP server has received 62744 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.250Z SendDataTCPServer.js: TCP/IP server has received 63756 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.261Z SendDataTCPServer.js: TCP/IP server has received 64768 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.273Z SendDataTCPServer.js: TCP/IP server has received 65780 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.281Z SendDataTCPServer.js: TCP/IP server has received 66792 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.289Z SendDataTCPServer.js: TCP/IP server has received 67804 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.294Z SendDataTCPServer.js: TCP/IP server has received 68816 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.394Z SendDataTCPServer.js: TCP/IP server has received 69828 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.399Z SendDataTCPServer.js: TCP/IP server has received 70840 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.404Z SendDataTCPServer.js: TCP/IP server has received 71852 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.436Z SendDataTCPServer.js: TCP/IP server has received 76912 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.442Z SendDataTCPServer.js: TCP/IP server has received 77924 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.543Z SendDataTCPServer.js: TCP/IP server has received 78936 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.550Z SendDataTCPServer.js: TCP/IP server has received 79948 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.557Z SendDataTCPServer.js: TCP/IP server has received 80960 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.567Z SendDataTCPServer.js: TCP/IP server has received 81972 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.605Z SendDataTCPServer.js: TCP/IP server has received 83996 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.608Z SendDataTCPServer.js: TCP/IP server has received 85008 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.656Z SendDataTCPServer.js: TCP/IP server has received 86020 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.695Z SendDataTCPServer.js: TCP/IP server has received 87032 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.712Z SendDataTCPServer.js: TCP/IP server has received 88044 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.720Z SendDataTCPServer.js: TCP/IP server has received 89056 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.728Z SendDataTCPServer.js: TCP/IP server has received 90068 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.756Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 6060): 
,E/bt-btm  ( 2654): tBTM_SEC_DEV:0xa45c2b7c rs_disc_pending=0
,W/bt-btif ( 2654): bta_dm_check_av:0
,W/bt-btif ( 2654): btif_dm_cback : unhandled event (14)
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/jxcore-log( 6060): 2016-01-12T12:24:44.871Z SendDataTCPServer.js: TCP/IP server has received 92092 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.885Z SendDataTCPServer.js: TCP/IP server has received 93104 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.891Z SendDataTCPServer.js: TCP/IP server has received 94116 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.949Z SendDataTCPServer.js: TCP/IP server has received 95128 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.956Z SendDataTCPServer.js: TCP/IP server has received 96140 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:44.964Z SendDataTCPServer.js: TCP/IP server has received 97152 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:45.013Z SendDataTCPServer.js: TCP/IP server has received 98164 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:45.028Z SendDataTCPServer.js: TCP/IP server has received 99176 bytes of data
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:45.035Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6060): 
,W/bt-btif ( 2654): invalid rfc slot id: 11
,W/io.jxcore.node.StreamCopyingThread( 6060): Either failed to read from the output stream or write to the input stream (thread ID: 1065, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6060): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 6060): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB A5-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1063
,D/io.jxcore.node.IncomingSocketThread( 6060): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6060): doStop: Thread ID: 1065
D/io.jxcore.node.IncomingSocketThread( 6060): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 6060): doStop: Thread ID: 1064
D/io.jxcore.node.IncomingSocketThread( 6060): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6060): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6060): Either failed to read from the output stream or write to the input stream (thread ID: 1064, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6060): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6060): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB A5-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 6060): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread( 6060): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6060): closeBluetoothSocketAndStreams
,D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@20c7a4e2, channel: 6, state: CONNECTED
,D/BluetoothSocket( 6060): close() this: android.bluetooth.BluetoothSocket@20c7a4e2, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@320a4073, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@39f2ab30mSocket: android.net.LocalSocket@339bb3a9 impl:android.net.LocalSocketImpl@7bf2d2e fd:FileDescriptor[113]
D/BluetoothSocket( 6060): Closing mSocket: android.net.LocalSocket@339bb3a9 impl:android.net.LocalSocketImpl@7bf2d2e fd:FileDescriptor[113]
,D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@20c7a4e2, channel: 6, state: CLOSED
,D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@20c7a4e2, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6060): Exiting thread (ID: 1064, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6060): Exiting thread (ID: 1065, name: Receiver)
,I/jxcore-log( 6060): 2016-01-12T12:24:45.142Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:45.200Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:45.200Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6060): 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged,
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/bt-btm  ( 2654): tBTM_SEC_DEV:0xa45c29b8 rs_disc_pending=1,
,W/bt-btif ( 2654): bta_dm_check_av:0
W/bt-btif ( 2654): btif_dm_cback : unhandled event (14)
,E/SMD     (  289): DCD OFF
,E/bt-btm  ( 2654): tBTM_SEC_DEV:0xa45c2b7c rs_disc_pending=1
,E/bt-btm  ( 2654): Reset sec_bd_name and name flag. (BR/EDR link)
E/bt-btm  ( 2654): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2654): bta_dm_check_av:0
W/bt-btif ( 2654): btif_dm_cback : unhandled event (14)
,D/KeyguardViewMediator( 1177): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1361): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/KeyguardViewMediator( 1177): isGear1: device is not B1!
,D/BluetoothAdapterService( 2654): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35e3bb96
,D/BtConfig.SecureMode( 2654): isSecureModeOn:false
,D/SecContentProvider( 1019): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2654): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5936): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5936): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 2654): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2654): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1177): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/BluetoothAdapterService( 2654): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35e3bb96
,D/BtConfig.SecureMode( 2654): isSecureModeOn:false
,D/SecContentProvider( 1019): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,E/BluetoothEventManager( 1361): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 1177): isGear1: device is not B1!
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/BluetoothPbapService( 2654): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5936): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5936): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): setState: RESTARTING
,D/WifiP2pService( 1019): InactiveState{ what=139268 }
,I/wpa_supplicant( 1398): P2P-FIND-STOPPED 
,D/WifiP2pService( 1019): InactiveState{ what=147493 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1019): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  289): DCD OFF
,D/io.jxcore.node.ConnectionHelper( 6060): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
,E/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6060): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
,I/jxcore-log( 6060): 2016-01-12T12:24:50.205Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:24:50.205Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:50.206Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:24:50.206Z SendDataConnector.js: do connect now
I/jxcore-log( 6060): 
,I/io.jxcore.node.ConnectionHelper( 6060): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6060): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): connect: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): connect: Trying to start connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): onConnecting: Thali Test (Galaxy A3) 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): connect: Started connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 6060): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 1066)
,D/BluetoothUtils( 6060): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 6060): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2654): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 2654): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_VER, value 7:8709
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 2654): db_query_execute: result 1
D/BluetoothSocket( 6060): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,D/IOP_DB_BT( 2654): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2654): db_query_execute: result 1
,W/bt-btif ( 2654): info:x10
,D/        ( 2654): remote version info [08:ec:a9:50:76:27]: 7, f, 610c
,D/KeyguardViewMediator( 1177): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_ACL_CONNECTED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1361): onReceive
,D/KeyguardViewMediator( 1177): isGear1: device is not B1!
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5936): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5936): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 2654): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2654): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1177): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1361): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/KeyguardViewMediator( 1177): isGear1: device is not B1!
,D/BluetoothAdapterService( 2654): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35e3bb96
D/BtConfig.SecureMode( 2654): isSecureModeOn:false
,D/SecContentProvider( 1019): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2654): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5936): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5936): Bluetooth Device Name: A5-1
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.NAME_CHANGED
,E/SMD     (  289): DCD OFF
,E/bt-btm  ( 2654): tBTM_SEC_DEV:0xa45c2b7c rs_disc_pending=1
,W/bt-btif ( 2654): bta_dm_check_av:0
W/bt-btif ( 2654): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): Start timer timeout, starting now...
,D/WifiP2pService( 1019): InactiveState{ what=139265 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139265 }
D/WifiService( 1019): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1019): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiStateMachine( 1019): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1398): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1019): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,W/bt-sdp  ( 2654): process_service_search_attr_rsp
,E/Watchdog( 1019): !@Sync 21
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,W/bt-btif ( 2654): new conn_srvc id:26, app_id:1,
,W/bt-btif ( 2654): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2654): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2654): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): onSocketConnected: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1066)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): onBytesWritten: 63 bytes successfully written (thread ID: 1067)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Outgoing connection initialized (*handshake* thread ID: 1067)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Exiting thread (thread ID: 1066)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): Entering thread (ID: 1067)
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): onBytesRead: Read 81 bytes successfully (thread ID: 1067)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Handshake succeeded with [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): onHandshakeSucceeded: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): Exiting thread (ID: 1067)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): onConnected: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper( 6060): onConnected: Outgoing connection to peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/io.jxcore.node.ConnectionHelper( 6060): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6060): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6060): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 6060): Entering thread (ID: 1068)
D/io.jxcore.node.OutgoingSocketThread( 6060): Server socket local port: 47949
I/io.jxcore.node.OutgoingSocketThread( 6060): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 6060): onListeningForIncomingConnections: Outgoing connection is using port 47949 (peer ID: 08:EC:A9:50:76:27)
,I/jxcore-log( 6060): 2016-01-12T12:24:56.325Z SendDataConnector.js: CLIENT connected to 47949, error: null
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:24:56.326Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6060): 
,I/io.jxcore.node.OutgoingSocketThread( 6060): Incoming data from address: /127.0.0.1, port: 47949
,D/io.jxcore.node.OutgoingSocketThread( 6060): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6060): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6060): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6060): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6060): Exiting thread (ID: 1068)
,I/jxcore-log( 6060): 2016-01-12T12:24:56.335Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6060): 
,D/io.jxcore.node.StreamCopyingThread( 6060): Entering thread (ID: 1070, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6060): Entering thread (ID: 1069, name: Sender)
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/        ( 2654): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:3324
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 XT1072], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): restart: Restarting...
,D/WifiP2pService( 1019): InactiveState{ what=139307 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1019): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService( 1019): InactiveState{ what=139301 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 6060): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service request added successfully
,D/btif_config_util( 2654): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/WifiP2pService( 1019): InactiveState{ what=139310 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1019): P2pEnabledState discover services
,D/WifiService( 1019): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1019): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1019): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true,
D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1398): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service discovery started successfully,
,E/SMD     (  289): DCD OFF
,D/        ( 2654): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:66932
,I/jxcore-log( 6060): 2016-01-12T12:24:59.150Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6060): 
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
,D/        ( 2654): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:58508
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,I/jxcore-log( 6060): 2016-01-12T12:24:59.220Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6060): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/        ( 2654): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:48388
,I/jxcore-log( 6060): 2016-01-12T12:24:59.779Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6060): 
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/WifiP2pService( 1019): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
D/WifiP2pService( 1019): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 7E.18.23 p2p_dev_addr=7E.18.23 pri_dev_type=10-0050F204-5  ' A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 },
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,E/bt-btm  ( 2654): tBTM_SEC_DEV:0xa45c2b7c rs_disc_pending=0
,W/bt-btif ( 2654): bta_dm_check_av:0
W/bt-btif ( 2654): btif_dm_cback : unhandled event (14)
,D/        ( 2654): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:38268
,I/jxcore-log( 6060): 2016-01-12T12:25:01.292Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6060): 
,E/SMD     (  289): DCD OFF
,E/bt-btm  ( 2654): tBTM_SEC_DEV:0xa45c2b7c rs_disc_pending=0,
W/bt-btif ( 2654): bta_dm_check_av:0
W/bt-btif ( 2654): btif_dm_cback : unhandled event (14)
,D/        ( 2654): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:28148
,I/jxcore-log( 6060): 2016-01-12T12:25:02.846Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6060): 
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,E/bt-btm  ( 2654): tBTM_SEC_DEV:0xa45c2b7c rs_disc_pending=0,
W/bt-btif ( 2654): bta_dm_check_av:0
W/bt-btif ( 2654): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6060): 2016-01-12T12:25:04.137Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6060): 
,D/        ( 2654): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:18028
,E/SMD     (  289): DCD OFF
,I/jxcore-log( 6060): 2016-01-12T12:25:04.541Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6060): 
,D/        ( 2654): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:7908
,I/jxcore-log( 6060): 2016-01-12T12:25:04.716Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6060): 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/jxcore-log( 6060): 2016-01-12T12:25:05.397Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6060): 
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1019): InactiveState{ what=147477 },
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,I/jxcore-log( 6060): 2016-01-12T12:25:05.597Z SendDataConnector.js: CLIENT is data received : 100000,
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:25:05.597Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6060): 
I/jxcore-log( 6060): oneRoundDownNow
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:25:05.598Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:25:05.598Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6060): 
D/io.jxcore.node.ConnectionHelper( 6060): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 6060): close
D/io.jxcore.node.OutgoingSocketThread( 6060): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6060): doStop: Thread ID: 1070
D/io.jxcore.node.OutgoingSocketThread( 6060): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6060): doStop: Thread ID: 1069
D/io.jxcore.node.OutgoingSocketThread( 6060): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6060): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 6060): Either failed to read from the output stream or write to the input stream (thread ID: 1069, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6060): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6060): onDisconnected: Outgoing connection, peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 6060): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6060): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6060): closeBluetoothSocketAndStreams
,D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@2bbe70cf, channel: 6, state: CONNECTED
D/BluetoothSocket( 6060): close() this: android.bluetooth.BluetoothSocket@2bbe70cf, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@358f4a5c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@15d2e165mSocket: android.net.LocalSocket@494ee3a impl:android.net.LocalSocketImpl@edb4aeb fd:FileDescriptor[111]
D/BluetoothSocket( 6060): Closing mSocket: android.net.LocalSocket@494ee3a impl:android.net.LocalSocketImpl@edb4aeb fd:FileDescriptor[111]
W/io.jxcore.node.StreamCopyingThread( 6060): Either failed to read from the output stream or write to the input stream (thread ID: 1070, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6060): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6060): onDisconnected: Outgoing connection, peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@2bbe70cf, channel: 6, state: CLOSED
D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@2bbe70cf, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6060): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:76:27
I/jxcore-log( 6060): 2016-01-12T12:25:05.602Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 6060): 
I/jxcore-log( 6060): ---- round done--------
I/jxcore-log( 6060): 
I/jxcore-log( 6060): startWithNextDevice
I/jxcore-log( 6060): 
I/jxcore-log( 6060): do fake peer & start
I/jxcore-log( 6060): 
I/jxcore-log( 6060): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:25:05.603Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:25:05.603Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 6060): 
E/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left,
D/io.jxcore.node.StreamCopyingThread( 6060): Exiting thread (ID: 1069, name: Sender)
E/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6060): Exiting thread (ID: 1070, name: Receiver)
I/jxcore-log( 6060): 2016-01-12T12:25:05.603Z SendDataConnector.js: do connect now
I/jxcore-log( 6060): 
I/io.jxcore.node.ConnectionHelper( 6060): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 6060): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): connect: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): onConnecting: null 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): connect: Started connecting to null in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 6060): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 1071)
,D/BluetoothUtils( 6060): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 6060): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2654): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 6060): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
,D/IOP_DB_BT( 2654): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 2654): db_query_execute: result 1
E/bt-btm  ( 2654): tBTM_SEC_DEV:0xa45c2b7c rs_disc_pending=1
,W/bt-btif ( 2654): bta_dm_check_av:0
W/bt-btif ( 2654): btif_dm_cback : unhandled event (14)
,E/SMD     (  289): DCD OFF
,W/bt-btif ( 2654): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1019): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiP2pService( 1019): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1019): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): restart: Restarting...
,D/WifiP2pService( 1019): InactiveState{ what=139301 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1019): P2pEnabledState add service request,
,D/WifiP2pManager( 6060): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service request added successfully,
,D/WifiP2pService( 1019): InactiveState{ what=139310 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1019): P2pEnabledState discover services
,D/WifiService( 1019): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1019): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1019): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1398): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service discovery started successfully
,E/SMD     (  289): DCD OFF
,I/jxcore-log( 6060): timeout now
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): weAreDoneNow, resultArray.length: 2
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): sendReportNow
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): done, now sending data to server
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:25:10.622Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6060): 
,D/io.jxcore.node.ConnectionHelper( 6060): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
E/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6060): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:3F:54:73:64:C0), either no such connection or failed to close the connection
,I/jxcore-log( 6060): 2016-01-12T12:25:10.625Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 6060): 
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 Note4-1] already in the list, will not add again
,E/SMD     (  289): DCD OFF,
,W/bt-sdp  ( 2654): SDP - Rcvd conn cnf with error: 0x4  CID 0x46,
E/bt-btif ( 2654): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2654): invalid rfc slot id: 16
,D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@f4b048, channel: -1, state: INIT
D/BluetoothSocket( 6060): close() this: android.bluetooth.BluetoothSocket@f4b048, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@15952ee1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@7d3b406mSocket: android.net.LocalSocket@18a1aac7 impl:android.net.LocalSocketImpl@1bc888f4 fd:FileDescriptor[111]
D/BluetoothSocket( 6060): Closing mSocket: android.net.LocalSocket@18a1aac7 impl:android.net.LocalSocketImpl@1bc888f4 fd:FileDescriptor[111]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 1071)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Maximum number of allowed retries (0) reached, giving up... (thread ID: 1071)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Exiting thread (thread ID: 1071)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [58:3F:54:73:64:C0 G3-1]
I/jxcore-log( 6060): 2016-01-12T12:25:13.577Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [58:3F:54:73:64:C0 G3-1] failed
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:25:13.577Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [58:3F:54:73:64:C0 G3-1] failed
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:25:13.578Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6060): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): shutdown (thread ID: 1071)
D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@f4b048, channel: -1, state: CLOSED
,D/WifiP2pService( 1019): InactiveState{ what=147494 },
D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,E/SMD     (  289): DCD OFF
,I/jxcore-log( 6060): 2016-01-12T12:25:18.578Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:25:18.579Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 6060): 
,E/bt-btm  ( 2654): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2654): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1177): Received android.bluetooth.device.action.ACL_DISCONNECTED,
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1361): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2654): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35e3bb96
,D/BtConfig.SecureMode( 2654): isSecureModeOn:false
,D/SecContentProvider( 1019): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/KeyguardViewMediator( 1177): isGear1: device is not B1!
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2654): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5936): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5936): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
I/wpa_supplicant( 1398): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1019): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1019): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1019): P2pEnabledState clear service request
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService( 1019): InactiveState{ what=139301 },
D/WifiP2pService( 1019): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1019): P2pEnabledState add service request
D/WifiP2pManager( 6060): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service request added successfully
,E/SMD     (  289): DCD OFF
,D/WifiP2pService( 1019): InactiveState{ what=139310 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1019): P2pEnabledState discover services
,D/WifiStateMachine( 1019): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1019): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1019): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1398): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service discovery started successfully,
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/WifiP2pService( 1019): InactiveState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1019): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/io.jxcore.node.ConnectionHelper( 6060): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 6060): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,E/SMD     (  289): DCD OFF
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/WifiP2pService( 1019): InactiveState{ what=147477 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147477 }
,I/wpa_supplicant( 1398): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
D/WifiDisplayController( 1019): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
,D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1019): DefaultState{ what=139283 }
D/WifiDisplayController( 1019): Received list of peers.
D/WifiP2pService( 1019): InactiveState{ what=139283 }
D/WifiDisplayController( 1019):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1019): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1019):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1019):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1019):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1019):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1019):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1019): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1019):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 Nexus 5], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 Nexus 5]
,D/io.jxcore.node.ConnectionHelper( 6060): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
,E/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 6060): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6060): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:3F:54:73:64:C0), either no such connection or failed to close the connection
I/jxcore-log( 6060): 2016-01-12T12:25:23.581Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:25:23.582Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:25:23.582Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 6060): 
I/jxcore-log( 6060): 2016-01-12T12:25:23.582Z SendDataConnector.js: do connect now
I/jxcore-log( 6060): 
I/io.jxcore.node.ConnectionHelper( 6060): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 6060): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): connect: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): onConnecting: null 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): connect: Started connecting to null in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 6060): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 1073)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 6060): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 6060): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2654): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/IOP_DB_BT( 2654): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_DIR_ALL, value 1
D/BluetoothSocket( 6060): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
D/IOP_DB_BT( 2654): db_query_execute: result 1
,E/Watchdog( 1019): !@Sync 22
,I/PowerManagerService( 1019): [PWL] Off : 600s ago,
I/PowerManagerService( 1019): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1019): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1019): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=2654, ws=null) (elapsedTime=431)
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/IOP_DB_BT( 2654): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 2654): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2654): db_query_execute: result 1
W/bt-btif ( 2654): info:x10
D/        ( 2654): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2654): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.NAME_CHANGED
,I/jxcore-log( 6060): teardown
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): testSendData stopped
I/jxcore-log( 6060): 
,I/io.jxcore.node.ConnectionHelper( 6060): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): shutdown
,D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@ed4d81d, channel: 6, state: LISTENING
D/BluetoothSocket( 6060): close() this: android.bluetooth.BluetoothSocket@ed4d81d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11c7a4a3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2de70a92mSocket: android.net.LocalSocket@2f842c63 impl:android.net.LocalSocketImpl@385f4060 fd:FileDescriptor[110]
D/BluetoothSocket( 6060): Closing mSocket: android.net.LocalSocket@2f842c63 impl:android.net.LocalSocketImpl@385f4060 fd:FileDescriptor[110]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6060): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6060): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6060): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6060): release: No more listeners, de-initializing...
,D/WifiP2pService( 1019): InactiveState{ what=139298 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139298 }
,D/WifiP2pService( 1019): P2pEnabledState clear service
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6060): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6060): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6060): setState: NOT_STARTED
,I/jxcore-log( 6060): StopBroadcasting went ok
I/jxcore-log( 6060): 
,I/jxcore-log( 6060): 2016-01-12T12:25:27.655Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 6060): 
,I/chromium( 6060): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 6060): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6060): onDiscoveryManagerStateChanged: NOT_STARTED
,W/bt-sdp  ( 2654): process_service_search_attr_rsp
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 2654): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
,V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.CLASS_CHANGED
,D/SecContentProvider( 1019): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2654): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 2654): isSecureModeOn:false
,I/BluetoothBondStateMachine( 2654): Entering PendingCommandState State
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,E/bt-btif ( 2654): check_cod: remote_cod = 0x5a020c
,D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
E/SMD     (  289): DCD OFF
V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1361): onReceive
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5887): BTStateChangeCB is registed
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
E/BluetoothHeadset( 5887): BluetoothHeadset service is binded
D/GMFPReceiver( 5887): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5887): jangil::setProperties()
,D/GMFPReceiver( 5887): jangil::printBTStatus()
,D/SettingsProvider( 1019): name = Wearable0001
I/jxcore-log( 6060): ****TEST TOOK:  ms ****
I/jxcore-log( 6060): 
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
I/jxcore-log( 6060): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6060): 
,D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10098
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/GMFPReceiver( 5887): ::::::::Wearable0001::false
D/SettingsProvider( 1019): name = Wearable0002
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10098
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/GMFPReceiver( 5887): ::::::::Wearable0002::false
D/GMFPReceiver( 5887): onServiceConnected() : 1
D/GMFPReceiver( 5887): mBluetoothHeadset = true
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6060): Local services cleared successfully
I/wpa_supplicant( 1398): P2P-FIND-STOPPED 
D/WifiP2pService( 1019): InactiveState{ what=139268 }
D/WifiP2pService( 1019): InactiveState{ what=139307 }
D/WifiP2pService( 1019): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1019): P2pEnabledState clear service request
D/WifiP2pService( 1019): remove channel information from framework
D/WifiP2pService( 1019): InactiveState{ what=147493 }
D/WifiP2pService( 1019): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1019): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6060): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6060): Service requests cleared successfully
,D/btif_config_util( 2654): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2654): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2654): Failed to remove device: 58:3F:54:73:64:C0
,D/SecContentProvider( 1019): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2654): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
D/BtConfig.SecureMode( 2654): isSecureModeOn:false
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1019): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/HidService( 2654): getHidService(): returning com.android.bluetooth.hid.HidService@339cae18
V/BluetoothEventManager( 1361): Received android.bluetooth.device.action.BOND_STATE_CHANGED
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/SettingsProvider( 1019): name = bluetooth_input_device_priority_58:3F:54:73:64:C0
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,D/HidService( 2654): Saved priority 58:3F:54:73:64:C0 = -1
,D/SettingsProvider( 1019): name = bluetooth_a2dp_sink_priority_58:3F:54:73:64:C0
,D/BluetoothNotiBroadcastReceiver( 1361): onReceive
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
D/SettingsProvider( 1019): name = bluetooth_headset_priority_58:3F:54:73:64:C0
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 1002
,D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,I/BluetoothBondStateMachine( 2654): StableState(): Entering Off State
,E/BluetoothHeadset( 5887): BTStateChangeCB is registed
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5887): BluetoothHeadset service is binded
D/GMFPReceiver( 5887): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5887): jangil::setProperties()
,D/GMFPReceiver( 5887): jangil::printBTStatus()
,D/SettingsProvider( 1019): name = Wearable0001
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
,D/SettingsProvider( 1019): selectionArgs: 10098
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,D/GMFPReceiver( 5887): ::::::::Wearable0001::false
,D/SettingsProvider( 1019): name = Wearable0002
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10098
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/GMFPReceiver( 5887): ::::::::Wearable0002::false
,D/GMFPReceiver( 5887): onServiceConnected() : 1
D/GMFPReceiver( 5887): mBluetoothHeadset = true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/AndroidRuntime( 6788): 
D/AndroidRuntime( 6788): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6788): CheckJNI is OFF
,D/AndroidRuntime( 6788): readGMSProperty: start
D/AndroidRuntime( 6788): readGMSProperty: already setted!!
D/AndroidRuntime( 6788): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6788): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6788): readGMSProperty: end
D/AndroidRuntime( 6788): addProductProperty: start
,W/bt-btif ( 2654): new conn_srvc id:26, app_id:1,
W/bt-btif ( 2654): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2654): bta_dm_pm_ssr:2, lat:1200
E/BluetoothRemoteDevices( 2654): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): onSocketConnected: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 1073)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): shutdown (thread ID: 1073)
D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@306bd919, channel: 5, state: CONNECTED
,D/BluetoothSocket( 6060): close() this: android.bluetooth.BluetoothSocket@306bd919, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c673dde, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@24832bbfmSocket: android.net.LocalSocket@17e8028c impl:android.net.LocalSocketImpl@22d7edd5 fd:FileDescriptor[111]
D/BluetoothSocket( 6060): Closing mSocket: android.net.LocalSocket@17e8028c impl:android.net.LocalSocketImpl@22d7edd5 fd:FileDescriptor[111]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): Entering thread (ID: 1075),
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): Disconnected: socket closed
E/AffinityControl( 6788): AffinityControl: registerfunction enter
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): onDisconnected: [null null null] (thread ID: 1075)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6060): onConnectionFailed: Socket disconnected
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): shutdown (thread ID: 1073)
D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@306bd919, channel: 5, state: CLOSED
D/BluetoothSocket( 6060): close() in, this: android.bluetooth.BluetoothSocket@306bd919, channel: 5, state: CLOSED,
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): Exiting thread (ID: 1075)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6060): onConnectionFailed: Socket disconnected [null null null]
D/AndroidRuntime( 6060): Shutting down VM
E/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): write: Failed to write to output stream: socket closed
E/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): java.io.IOException: socket closed
E/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): 	at android.net.LocalSocketImpl$SocketOutputStream.write(LocalSocketImpl.java:130)
E/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): 	at android.bluetooth.BluetoothSocket.write(BluetoothSocket.java:659)
E/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): 	at android.bluetooth.BluetoothOutputStream.write(BluetoothOutputStream.java:85)
E/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): 	at java.io.OutputStream.write(OutputStream.java:82)
E/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): 	at org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.write(BluetoothSocketIoThread.java:162)
E/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6060): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:182)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6060): Exiting thread (thread ID: 1073)
,W/bt-btif ( 2654): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,D/AndroidRuntime( 6788): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 1019): START PACKAGE DELETE: observer{214620028}
D/PackageManager( 1019): pkg{<packageName>}
D/PackageManager( 1019): user{0}
D/PackageManager( 1019): caller{2000}
D/PackageManager( 1019): flags{3}
,D/PersonaManagerService( 1019): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved : true
,D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1019): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager( 1019): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager( 1019): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService( 1019): deletePackage- pkg:com.test.thalitest, edmuserId:0,
D/PackageManagerService( 1019): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1019): !@killApplicatoin: 10338, uninstall pkg
,I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 6060:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1019): Skipping PackageSetting{2bae1185 com.example.hello/10346} due to missing metadata
,I/WindowState( 1019): WIN DEATH: Window{144867d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{306a45e3 u0 com.test.thalitest/.MainActivity t20}
,D/InputDispatcher( 1019): Focus left window: 6060
,D/InputDispatcher( 1019): Focused application released
W/ActivityManager( 1019): Spurious death for ProcessRecord{25edb805 6060:com.test.thalitest/u0a338}, curProc for 6060: null
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 4002): Explicit concurrent mark sweep GC freed 3204(192KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 905us total 25.696ms
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 5936): Explicit concurrent mark sweep GC freed 19699(1082KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 6MB/8MB, paused 795us total 45.716ms
,E/SamsungIME( 1783): mOCRHelper is null
,W/GeofencerStateMachine( 1726): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.5.123: ( 3707): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 12 13:25:29 GMT+01:00 2016
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3707): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1019): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
D/EnterpriseDeviceManagerService( 1019): Package has changed for user 0
I/splitIntent( 1019): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
D/EnterpriseDeviceManagerService( 1019): Admin package name: com.google.android.gms
I/splitIntent( 1019): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,W/TextServicesManagerService( 1019): no available spell checker services found
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 3707): KLMSIntentService(): onCreate()
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 6802): MountEmulatedStorage()
E/Zygote  ( 6802): v2
I/libpersona( 6802): KNOX_SDCARD checking this for 10090
I/libpersona( 6802): KNOX_SDCARD not a persona
I/SELinux ( 6802): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/KLMS-2.5.123: ( 3707): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6802 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6802): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SELinux ( 6802): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3707): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3707): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3707): KLMSIntentService(): PACKAGE_REMOVED
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/KLMS-2.5.123: ( 3707): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.123: ( 3707): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 6802): TimaSignature is unavailable
,D/ActivityThread( 6802): Added TimaKeyStore provider
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 47575(5MB) AllocSpace objects, 38(612KB) LOS objects, 33% free, 24MB/37MB, paused 7.918ms total 227.155ms
,I/art     ( 1019): WaitForGcToComplete blocked for 149.885ms for cause Explicit
,D/RegisteredServicesCache( 1438): empty dynamic service
,D/elm:15121( 6802): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6802): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6802): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6802): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/KLMS-2.5.123: ( 3707): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:15121( 6802): ElmAgentService : onCreate()
,D/elm:15121( 6802): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 6802): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6802): MDMBridge.getInstance()
D/elm:15121( 6802): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 6802): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 3707): KLMSIntentService(): onDestroy()
,D/elm:15121( 6802): ElmAgentService : onDestroy().
,I/ActivityManager( 1019): Killing 5808:com.wsomacp/u0a23 (adj 15): empty #31
,W/ResourceType( 1019): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService( 1019): PackageReceiver onReceive()
,I/HarmonyEASService( 1019): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/ResourcesManager( 1019): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/KnoxMUMContainerPolicy( 1019): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 12828(624KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/37MB, paused 3.399ms total 184.745ms
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1019): clearDefaults: com.test.thalitest
,D/PackageManager( 1019): delete codoeFile: 
,I/CrashAnrDetector( 1019): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1019): failed to open /acct/uid_10023/pid_5808/cgroup.procs: No such file or directory
,D/AASAuninstall( 1019): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
,I/AASA_removePackage( 1019): UID=10338 Target=com.test.thalitest
,D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/PackageManager( 1019): result of delete: 1{214620028}
D/JobSchedulerService( 1019): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10338
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/AndroidRuntime( 6788): Shutting down VM
,V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10338
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
,D/TaskPersister( 1019): removeObsoleteFile: deleting file=20_task.xml
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
,D/SSRM:aZ ( 1019): MSG_TYPE_APP_REMOVED::
,I/PCWCLIENTTRACE_PushUtil( 5638): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5638): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5638): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5638): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6819): MountEmulatedStorage(),
I/libpersona( 6819): KNOX_SDCARD checking this for 10029
E/Zygote  ( 6819): v2
I/libpersona( 6819): KNOX_SDCARD not a persona,
I/SELinux ( 6819): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6819 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 6819): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6819): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6819): TimaSignature is unavailable
,D/ActivityThread( 6819): Added TimaKeyStore provider
,I/FeatureConfig( 6819): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/SA      ( 5722): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5722): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager( 1019): Killing 4950:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,E/JavaBinder( 1019): !!! FAILED BINDER TRANSACTION !!!
,W/ResourcesManager( 6819): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6819): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/BroadcastQueue( 1019): Exception when sending broadcast to ComponentInfo{com.sec.android.gallery3d/com.sec.android.gallery3d.app.PackagesMonitor}
W/BroadcastQueue( 1019): android.os.TransactionTooLargeException
W/BroadcastQueue( 1019): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1019): 	at android.os.BinderProxy.transact(Binder.java:511),
W/BroadcastQueue( 1019): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1019): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1019): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1019): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
W/BroadcastQueue( 1019): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1019): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
W/BroadcastQueue( 1019): 	at android.os.Binder.execTransact(Binder.java:461)
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6819): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/Zygote  ( 6837): MountEmulatedStorage()
E/Zygote  ( 6837): v2
I/libpersona( 6837): KNOX_SDCARD checking this for 10039
I/libpersona( 6837): KNOX_SDCARD not a persona
I/SELinux ( 6837): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6837 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 6837): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6837): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 6819): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
W/ResourcesManager( 6819): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6819): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6819): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
W/ResourcesManager( 6819): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6819): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6819): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6837): TimaSignature is unavailable
,D/ActivityThread( 6837): Added TimaKeyStore provider
,W/ResourcesManager( 6819): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6819): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6819): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6837): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6837): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6837): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6819): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6819): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/libprocessgroup( 1019): failed to open /acct/uid_10039/pid_4950/cgroup.procs: No such file or directory
,W/art     ( 6788): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/ResourcesManager( 6819): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6819): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6819): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6819): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6819): system/finder_cp/cpdata.xml file not found
,E/SQLiteLog( 6837): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6837): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase( 6837): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6837): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6837): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6837): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase( 6837): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase( 6837): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6837): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6837): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6837): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6837): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6837): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6837): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6837): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6837): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6837): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6837): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6837): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/NearbySource( 6837): Nearby Source Create!
,D/NearbyContext( 6837): Nearby Context Create!
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6837): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 6837): Samsung link source created
,E/SQLiteLog( 6837): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,D/ContactProvider( 6837): getAllContactInfoList Start
,E/SQLiteDatabase( 6837): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase( 6837): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6837): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6837): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6837): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6837): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase( 6837): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase( 6837): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase( 6837): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
E/SQLiteDatabase( 6837): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
E/SQLiteDatabase( 6837): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 6837): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteDatabase( 6837): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6837): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6837): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6837): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6837): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6837): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6837): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6837): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6837): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper( 6837): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper( 6837): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6837): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6837): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6837): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6837): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6837): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6837): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6837): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6837): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6837): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6837): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper( 6837): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper( 6837): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper( 6837): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
E/SQLiteOpenHelper( 6837): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
E/SQLiteOpenHelper( 6837): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 6837): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteOpenHelper( 6837): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 6837): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 6837): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6837): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6837): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6837): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6837): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6837): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6837): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/SQLiteOpenHelper( 6837): Opened local.db in read-only mode
,D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}

```
