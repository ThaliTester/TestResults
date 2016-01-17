#### Test 561510933390750_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
D/SSRM:n  ( 1017): SIOP:: AP = 260
D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
--------- beginning of main
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2654): Disconnected process message: 10
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1017): waitForAlarm result :4
I/BooksSync( 6046): Starting books sync for 61035162, extras: ade
E/SMD     (  292): DCD OFF
I/BooksConfig( 6046): GmsCore Version = 7.8.99 (2134222-434)
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
D/AndroidRuntime( 6117): 
D/AndroidRuntime( 6117): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6117): CheckJNI is OFF
D/AndroidRuntime( 6117): readGMSProperty: start
D/AndroidRuntime( 6117): readGMSProperty: already setted!!
D/AndroidRuntime( 6117): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6117): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6117): readGMSProperty: end
D/AndroidRuntime( 6117): addProductProperty: start
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/GLSUser ( 1719): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1719): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1719): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1719): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1719): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
E/AffinityControl( 6117): AffinityControl: registerfunction enter
D/AndroidRuntime( 6117): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/art     ( 1017): Explicit concurrent mark sweep GC freed 44205(2MB) AllocSpace objects, 32(520KB) LOS objects, 33% free, 23MB/35MB, paused 3.153ms total 146.541ms
W/ActivityManager( 1017): mDVFSHelper.acquire()
D/FocusedStackFrame( 1017): Set to : 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6131): MountEmulatedStorage()
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
E/Zygote  ( 6131): v2
I/libpersona( 6131): KNOX_SDCARD checking this for 10338
I/libpersona( 6131): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6131 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 1481
D/AndroidRuntime( 6117): Shutting down VM
I/SELinux ( 6131): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/SELinux ( 6131): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6131): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, uhalitest
I/GLSUser ( 1719): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1719): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1719): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1719): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1719): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimaKeyStoreProvider( 6131): TimaSignature is unavailable
D/ActivityThread( 6131): Added TimaKeyStore provider
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1017): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
E/BooksAccountManager( 6046): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6046): Soft error
E/BooksSync( 6046): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6046): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6046): Sync error
E/BooksSync( 6046): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6046): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6046): Finished books sync
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 157151, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
V/ActivityThread( 1481): updateVisibility : ActivityRecord{2586bce1 token=android.os.BinderProxy@1b073f27 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1481): onTrimMemory. Level: 20
D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
I/WebViewFactory( 6131): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
W/art     ( 6117): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/LibraryLoader( 6131): Time to load native libraries: 4 ms (timestamps 7727-7731)
I/LibraryLoader( 6131): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6131): Binding Chromium to main looper Looper (main, tid 1) {537fdef}
I/LibraryLoader( 6131): Expected native library version number "",actual native library version number ""
I/chromium( 6131): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6131): Initializing chromium process, singleProcess=true
W/art     ( 6131): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6131): ApplicationContext is null in ApplicationStatus
W/chromium( 6131): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6131): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6131): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6131): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6131): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6131): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6131): Local Branch: 
I/Adreno-EGL( 6131): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6131): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6131):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/art     ( 6131): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6131): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 6131): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6131): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6131): CordovaWebView is running on device made by: samsung
W/art     ( 6131): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6131): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1017): Activity pause timeout for ActivityRecord{4cd9922 u0 com.test.thalitest/.MainActivity t20}
D/OpenGLRenderer( 6131): Render dirty regions requested: true
I/ServiceManager(  322): Waiting for service AtCmdFwd...
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
W/chromium( 6131): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6131): updateVisibility : ActivityRecord{1a19c418 token=android.os.BinderProxy@54ac98a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 6131): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6131): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1017): Focus entered window: 6131
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6131): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6131): Initialized EGL, version 1.4
D/OpenGLRenderer( 6131): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6131): Enabling debug mode 0
D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/Timeline( 6131): Timeline: Activity_idle id: android.os.BinderProxy@54ac98a time:158288
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
W/IInputConnectionWrapper( 6131): showStatusIcon on inactive InputConnection
I/ActivityManager( 1017): Displayed Component not be shown by security: +721ms (total +41s740ms)
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{4cd9922 u0 com.test.thalitest/.MainActivity t20} time:158297
W/ActivityManager( 1017): mDVFSHelper.release()
I/SurfaceFlinger(  258): id=13 Removed uhalitest (7/9)
I/SurfaceFlinger(  258): id=13 Removed uhalitest (-2/9)
I/SamsungIME( 1870): getCurrentCandidateView
W/BindingManager( 6131): Cannot call determinedVisibility() - never saw a connection for the pid: 6131
D/SamsungIME( 1870): Dismiss ExpandCandiate
I/SamsungIME( 1870): getDebugLevel  : 0x4f4c
D/JsMessageQueue( 6131): Set native->JS mode to OnlineEventsBridgeMode
I/SamsungIME( 1870): getDebugLevel  : 0x4f4c
I/SamsungIME( 1870): KeybaordView init() : load resources
I/SamsungIME( 1870): getCurrentKeyboard
I/SamsungIME( 1870): getTextKeyboard
D/SamsungIME( 1870): [SwiftkeyWrapper] currentLangauge : 1701729619
V/AlarmManager( 1017): waitForAlarm result :8
D/jxcore_app_log( 6131): JniHelper::setJavaVM(0xb6f54448), pthread_self() = -1219838320
D/JX-Cordova( 6131): jxcore cordova android initializing
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/jxcore-log( 6131): Initializing JXcore engine
W/jxcore-log( 6131): JXcore engine is ready
,W/jxcore-log( 6131): Starting JXcore engine
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF,
,E/audit   ( 1893): type=1400 msg=audit(1453032841.673:205): avc:  denied  { ioctl } for  pid=6131 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
E/audit   ( 1893):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1893): type=1300 msg=audit(1453032841.673:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=be971d58 items=0 ppid=308 ppcomm=main pid=6131 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1893): type=1320 msg=audit(1453032841.673:205): 
,W/jxcore-log( 6131): Platform android
W/jxcore-log( 6131): 
W/jxcore-log( 6131): Process ARCH arm
W/jxcore-log( 6131): 
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/jxcore-log( 6131): JXcore Cordova bridge is ready!
I/jxcore-log( 6131): 
,W/jxcore-log( 6131): JXcore engine is started
,I/Choreographer( 6131): Skipped 150 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6131): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6131): Toggling radios to true
I/jxcore-log( 6131): 
,D/BluetoothAdapter( 6131): enable()
,D/BluetoothAdapter( 6131): enable(): BT is already enabled..!,
,D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1017): mCursor = null
,D/WifiService( 1017): setWifiEnabled: true pid=6131, uid=10338
,W/ActivityManager( 1017): Permission Denial: getCurrentUser() from pid=6131, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1017): Failed getting userId using ActivityManagerNative
W/WifiService( 1017): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6131, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1017): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1017): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1017): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1017): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1017): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1017): name = wifi_on
,I/WifiService( 1017): disconnect: pid=6131, uid=10338
,I/wpa_supplicant( 1381): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6131): Radios toggled
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): My device name is: samsung-SM-A300FU
I/jxcore-log( 6131): 
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false,
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
D/Tethering( 1017): InitialState.processMessage what=4
I/wpa_supplicant( 1381): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1381): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1381): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1381): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1381): wlan0: State: DISCONNECTED -> DISCONNECTED
E/wpa_supplicant( 1381): Cmd 35605 not handled
E/WifiStateMachine( 1017): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1381): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1381): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1381): P2P: Current p2p state = IDLE
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,I/wpa_supplicant( 1381): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1381): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1381): First Scan Start
I/wpa_supplicant( 1381): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,E/Tethering( 1017): No numeric data
,D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering( 1017): clearTetheredNotification()
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x1)
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/HotspotTile( 1178): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1178): updateTetherState():false, false
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,V/NetworkStats( 1017): performPollLocked() took 7ms
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,E/WifiNative-wlan0( 1017): do suspend true,
,D/WifiP2pService( 1017): InactiveState{ what=143375 },
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/CommandListener(  279): Clearing all IP addresses on wlan0,
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ConnectivityService( 1017): updateNetworkInfo(),
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine( 1017): Start Disconnecting Watchdog 1
V/NativeCrypto( 1719): Read error: ssl=0xb74e9778: I/O error during system call, Connection timed out
I/wpa_supplicant( 1381): wlan0: Setting scan request: 0 sec 0 usec
,E/WifiNative-wlan0( 1017): do suspend true
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,V/NativeCrypto( 1719): SSL shutdown failed: ssl=0xb74e9778: I/O error during system call, Broken pipe
,D/ConnectivityService( 1017): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011,
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-3ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=-3ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/qtaguid ( 1017): Tagging socket 334 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qtaguid ( 1017): Untagging socket 334
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 1686): Starting #8
,I/Hs20UtilService( 1686): Message received 5007
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/CommandListener(  279): Clearing all IP addresses on wlan0
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
,D/ConnectivityService( 1017): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null,
,D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1017): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524292
D/ConnectivityService( 1017): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/CSLegacyTypeTracker( 1017): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/CSLegacyTypeTracker( 1017): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
D/TelephonyNetworkFactory( 1457): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1457): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WifiNetworkAgent( 1017): NetworkAgent: NetworkAgent channel lost
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
D/Tethering( 1017): MasterInitialState.processMessage what=3
D/ConnectivityService( 1017): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): doQuit - quitNow()
E/ConnectivityService( 1017): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,V/NetworkStats( 1017): updateIfacesLocked()
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x1)
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
,D/StatusBar.NetworkController( 1178): EthernetConnected: false
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1178): updateDataNetType()
D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1178): updateLTEICONDataNetType:0
,V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,V/NetworkStats( 1017): performPollLocked() took 7ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6187): MountEmulatedStorage(),
,E/Zygote  ( 6187): v2
I/libpersona( 6187): KNOX_SDCARD checking this for 10102
I/libpersona( 6187): KNOX_SDCARD not a persona
,I/SELinux ( 6187): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6187 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 6187): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6187): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/TimaKeyStoreProvider( 6187): TimaSignature is unavailable
,D/ActivityThread( 6187): Added TimaKeyStore provider
,W/ResourcesManager( 6187): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,I/Babel_SMS( 6187): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6187): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6187): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel_SMS( 6187): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6187): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6187): MmsConfig.loadFromResources
,E/Babel_SMS( 6187): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6187): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  284): getCameraInfo: X
W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  284): getCameraInfo: X
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
W/Settings( 6187): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6187): startup - clean
,I/Babel   ( 6187): deleted: false for 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1686): Starting #9
I/Hs20UtilService( 1686): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6187): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6187): Unsupported mime audio/evrc
,W/AudioCapabilities( 6187): Unsupported mime audio/qcelp
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6187): Unsupported mime audio/mpeg-L1
W/AudioCapabilities( 6187): Unsupported mime audio/mpeg-L2
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/AudioCapabilities( 6187): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6187): Unsupported mime audio/x-ima
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6187): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6187): Unsupported mime audio/evrc
,I/ApplicationPolicy( 1017): updateDataUsageMap
,W/VideoCapabilities( 6187): Unsupported mime video/wvc1
,W/VideoCapabilities( 6187): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6187): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6187): Unsupported mime video/wvc1
,W/VideoCapabilities( 6187): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6187): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6187): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6187): Unsupported mime video/mp43
,W/VideoCapabilities( 6187): Unsupported mime video/sorenson
,W/VideoCapabilities( 6187): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6187): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6187): Unrecognized profile 2130706433 for video/avc
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/VideoCapabilities( 6187): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6187): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6187): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1017): Killing 5597:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,I/vclib   ( 6187): onServiceConnected
,W/Babel   ( 6187): Attempted to change video mute state without an active call.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10135/pid_5597/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/PCWCLIENTTRACE_PushUtil( 5758): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5758): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5758): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5758): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1017): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
,I/splitIntent( 1017): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
,I/splitIntent( 1017): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/PCWCLIENTTRACE_SYSTEMReceiver( 5758): noConnectivity : true
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6231): MountEmulatedStorage()
,E/Zygote  ( 6231): v2
I/libpersona( 6231): KNOX_SDCARD checking this for 10108
I/libpersona( 6231): KNOX_SDCARD not a persona
,I/SELinux ( 6231): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6231 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6231): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6231): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6231): TimaSignature is unavailable
,D/ActivityThread( 6231): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 8685(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 26.065ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 16.579ms
,I/wpa_supplicant( 1381): nl80211: Received scan results (6 BSSes),
I/wpa_supplicant( 1381): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1381): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1381): Trying to associate with  'G700',
I/wpa_supplicant( 1381): Re-associate with C0.AA.48
I/wpa_supplicant( 1381): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1381): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
D/WifiMonitor( 1017): didn't find BSSID Trying to associate with SSID 'NG700'
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 16.691ms
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled,
D/SecContentProvider2( 1017): mCursor = null
,E/wpa_supplicant( 1381): Cmd 35605 not handled
,I/wpa_supplicant( 1381): wlan0: State: ASSOCIATING -> ASSOCIATED
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1381): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1381): Associated with C0.AA.48
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1381): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1381): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1381): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, true
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/Tethering( 1017): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 1381): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1381): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1381): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1381): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1381): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1381): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1381): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1381): Blacklist: Clear (temp) 
I/wpa_supplicant( 1381): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1017): mCursor = null
,E/Tethering( 1017): No numeric data
,D/Tethering( 1017): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering( 1017): clearTetheredNotification()
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/WifiNative-wlan0( 1017): callSECApiVoid - ID [50]
,D/HotspotTile( 1178): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1178): updateTetherState():false, false
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, true
E/WifiConfigStore( 1017): setLastSelectedConfiguration -1
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, true
D/Tethering( 1017): interfaceStatusChanged wlan0, true
,V/NetworkStats( 1017): performPollLocked() took 6ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/ConnectivityService( 1017): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1017): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/MusicStore( 6231): Database version: 120
,D/CommandListener(  279): Setting iface cfg
,E/WifiStateMachine( 1017): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1017): mCursor = null
,E/WifiNative-wlan0( 1017): do suspend false
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6231): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6231): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6231): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ResourcesManager( 6231): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6231): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6231): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/SQLiteLog( 1719): (10) POSIX Error : 11 SQLite Error : 3850
,W/ActivityThread( 6231): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6231): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@340b2cb4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6231): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6231): GMSCore installation verified
,I/ConfigStore( 6231): Config Database version: 1
,E/dhcpcd  ( 6255): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 6255): version 5.5.6 starting
,E/dhcpcd  ( 6255): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6255): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6255): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6255): if(wlan0) info get Success. (MAC : C0.AA.48)
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/dhcpcd  ( 6255): bssid match
,I/dhcpcd  ( 6255): wlan0: rebinding lease of 192.168.1.132
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1017): getStreamVolume 3 index 70
,I/MediaRouter( 6231): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6231): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6266): MountEmulatedStorage(),
E/Zygote  ( 6266): v2
I/libpersona( 6266): KNOX_SDCARD checking this for 10001
I/libpersona( 6266): KNOX_SDCARD not a persona,
I/SELinux ( 6266): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6266 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6266): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6266): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6266): TimaSignature is unavailable
,D/ActivityThread( 6266): Added TimaKeyStore provider
,I/GHttpClientFactory( 6231): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 6231): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1017): Killing 5633:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6285): MountEmulatedStorage(),
,E/Zygote  ( 6285): v2,
I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6285 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/libpersona( 6285): KNOX_SDCARD checking this for 1000
I/libpersona( 6285): KNOX_SDCARD not a persona
,I/SELinux ( 6285): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Killing 5649:com.wsomacp/u0a23 (adj 15): empty #31
I/SELinux ( 6285): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6285): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6285): TimaSignature is unavailable
,D/ActivityThread( 6285): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 6285): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] ,
,W/libprocessgroup( 1017): failed to open /acct/uid_10068/pid_5633/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10023/pid_5649/cgroup.procs: No such file or directory
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  292): DCD OFF,
,I/DIAGMON_AGENT( 6285): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6285): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6285): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE,
,I/DIAGMON_AGENT( 6285): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6285): ./extraInfo: <unknown ssid>
W/DIAGMON_AGENT( 6285): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6300 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6300): MountEmulatedStorage()
E/Zygote  ( 6300): v2
I/libpersona( 6300): KNOX_SDCARD checking this for 10008
I/libpersona( 6300): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Killing 5709:com.samsung.helphub/1000 (adj 15): empty #31
,I/SELinux ( 6300): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6300): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6300): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6300): TimaSignature is unavailable
,D/ActivityThread( 6300): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 5584:com.android.mms/u0a41 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3680): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sun Jan 17 13:14:04 GMT+01:00 2016
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3680): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 3680): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3680): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3680): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3680): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/Zygote  ( 6316): MountEmulatedStorage()
E/Zygote  ( 6316): v2
I/libpersona( 6316): KNOX_SDCARD checking this for 10031
I/libpersona( 6316): KNOX_SDCARD not a persona
I/SELinux ( 6316): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6316 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6316): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6316): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3680): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3680): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3680): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3680): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6316): TimaSignature is unavailable
,D/ActivityThread( 6316): Added TimaKeyStore provider
,I/SO_AGENT( 6316): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5800): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5800): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/SA      ( 5945): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5945): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 5945): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5800): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,I/SA      ( 5945): [SLFUCHKMGR] constructor called
,E/DBG_POLICYDM( 5800): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5800): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,D/CountryDetector( 1017): No listener is left
,I/SA      ( 5945): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5945): [OR] == isSIMCardReady false ==
,I/SA      ( 5945): [SCU] == networkStateCheck == false
I/SA      ( 5945): [OR] onReceive END
,I/ActivityManager( 1017): Killing 5252:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,V/DownloadManager( 1223): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1572): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1620): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1572): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1572): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1572): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1572): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1572): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1572): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5709/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10041/pid_5584/cgroup.procs: No such file or directory
,E/Zygote  ( 6333): MountEmulatedStorage(),
,E/Zygote  ( 6333): v2
,I/libpersona( 6333): KNOX_SDCARD checking this for 10121
I/libpersona( 6333): KNOX_SDCARD not a persona
,I/SELinux ( 6333): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6333 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6333): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6333): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6333): TimaSignature is unavailable
,D/ActivityThread( 6333): Added TimaKeyStore provider,
,W/ResourcesManager( 6333): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6333): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6333): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/libprocessgroup( 1017): failed to open /acct/uid_10014/pid_5252/cgroup.procs: No such file or directory
,D/QuickConnect( 6333): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6333): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6333): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6348): MountEmulatedStorage(),
,E/Zygote  ( 6348): v2
I/libpersona( 6348): KNOX_SDCARD checking this for 10141
I/libpersona( 6348): KNOX_SDCARD not a persona
,I/SELinux ( 6348): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6348 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5724:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/SELinux ( 6348): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6348): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6348): TimaSignature is unavailable
,D/ActivityThread( 6348): Added TimaKeyStore provider
,W/ResourcesManager( 6348): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6348): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6348): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6348): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId,
,W/libprocessgroup( 1017): failed to open /acct/uid_10032/pid_5724/cgroup.procs: No such file or directory
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/Zygote  ( 6371): MountEmulatedStorage(),
I/libpersona( 6371): KNOX_SDCARD checking this for 10068
E/Zygote  ( 6371): v2
I/libpersona( 6371): KNOX_SDCARD not a persona
I/SELinux ( 6371): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6371 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
,I/SELinux ( 6371): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6371): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 6371): TimaSignature is unavailable
,D/ActivityThread( 6371): Added TimaKeyStore provider
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/BadgeProvider( 6371): onCreate
D/BadgeProvider( 6371): DatabaseHelper
,I/dhcpcd  ( 6255): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6386): MountEmulatedStorage(),
E/Zygote  ( 6386): v2
I/libpersona( 6386): KNOX_SDCARD checking this for 1000
I/libpersona( 6386): KNOX_SDCARD not a persona
,I/SELinux ( 6386): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
D/BadgeProvider( 6371): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6386 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5161:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
I/ActivityManager( 1017): Killing 5743:com.sec.android.app.myfiles/u0a42 (adj 15): empty #32
,I/SELinux ( 6386): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6386): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6386): TimaSignature is unavailable
,D/ActivityThread( 6386): Added TimaKeyStore provider
,D/BadgeProvider( 6371): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6371): sendNotify, [notify] : null
D/BadgeProvider( 6371): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6371): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6371): update, [UpdateCount] : 1
,D/Launcher.Model( 1481): reloadBadges entered.
,I/dhcpcd  ( 6255): wlan0: leased 192.168.1.132 for 86400 seconds
,W/libprocessgroup( 1017): failed to open /acct/uid_10032/pid_5161/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10042/pid_5743/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found,
,D/SecurityLogAgent( 6386): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6386): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6386): StateMachine : Current State = 1
D/SecurityLogAgent( 6386): StateMachine : Changed Current State = 1,
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 53901(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 23MB/35MB, paused 4.030ms total 171.094ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/iu.Environment( 2002): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2002): num queued entries: 0
,I/iu.UploadsManager( 2002): num updated entries: 0
,I/iu.SyncManager( 2002): NEXT; no task
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2002): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6427): MountEmulatedStorage(),
,E/Zygote  ( 6427): v2,
I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6427 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
I/libpersona( 6427): KNOX_SDCARD checking this for 10032
,I/libpersona( 6427): KNOX_SDCARD not a persona
I/SELinux ( 6427): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/Babel   ( 6187): connection state changed from UNKNOWN to DISCONNECTED
,I/SELinux ( 6427): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Killing 5268:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
E/SELinux ( 6427): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,E/WifiNative-wlan0( 1017): do suspend true
,D/TimaKeyStoreProvider( 6427): TimaSignature is unavailable
,D/ActivityThread( 6427): Added TimaKeyStore provider
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1017): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,E/WifiStateMachine( 1017): VerifyingLinkState enter
,D/WifiNative-wlan0( 1017): callSECApiInt - ID [210]
,E/ConnectivityService( 1017): updateNetworkInfo()
,D/ConnectivityService( 1017): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null,
D/ConnectivityService( 1017): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1017): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1017): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/WifiWatchdogStateMachine.DnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 1017): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,E/WifiStateMachine( 1017): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1017): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1017): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1017): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1017): LTETest block dns file not exists
,D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/ConnectivityService( 1017): updateNetworkInfo()
,W/ActivityManager( 1017): Failed to clear dns cache for: com.samsung.android.app.galaxyfinder
,E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1017): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService( 1017):    accepting network in place of null
,D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1457): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/TelephonyNetworkFactory( 1457): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 1017): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1017): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 1000
,W/libprocessgroup( 1017): failed to open /acct/uid_10029/pid_5268/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,E/SPPClientService( 6427): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6427): [SystemStateMoniter] Current Time : 164355
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SPPClientService( 6427): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 6427): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6427): [PushClientApplication] Push log off : This is Ship build version
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6427): PushLog.txt file is not deleted.
,D/SPPClientService( 6427): PushLog.txt file is not deleted.
D/SPPClientService( 6427): ============PushLog. stop!
,E/Zygote  ( 6448): MountEmulatedStorage()
,E/Zygote  ( 6448): v2
I/libpersona( 6448): KNOX_SDCARD checking this for 10110
I/ActivityManager( 1017): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6448 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 6448): KNOX_SDCARD not a persona
,I/SELinux ( 6448): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Killing 5790:com.google.android.apps.docs/u0a87 (adj 15): empty #31,
,I/SELinux ( 6448): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6448): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ConnectivityService( 1017): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524290
D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1017): MasterInitialState.processMessage what=3
V/NetworkStats( 1017): updateIfacesLocked()
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
D/StatusBar.NetworkController( 1178): EthernetConnected: false
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1178): updateDataNetType()
D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1178): updateLTEICONDataNetType:0
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1017): mBoosterFLAG : 0
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
I/WifiTrafficPoller( 1017): current booster mode : FullMode
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/WifiNative-wlan0( 1017): callSECApiVoid - ID [212]
,V/NetworkStats( 1017): performPollLocked() took 9ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider( 6448): TimaSignature is unavailable
,D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/ActivityThread( 6448): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
E/SPPClientService( 6427): [[SystemStateMonitorService]] No Active Internet
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,I/System.out( 1017): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 17 Jan 2016 12:14:05 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453032845915], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453032845896]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
,D/ConnectivityService( 1017): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1178): EthernetConnected: false
,D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1178): updateDataNetType()
D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1178): updateLTEICONDataNetType:0
W/libprocessgroup( 1017): failed to open /acct/uid_10087/pid_5790/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6448): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6448): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6448):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6448):   adb logcat -s GAv4
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6448): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6448): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6448): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6448): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6448): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6448): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6448): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6448): Time to load native libraries: 2 ms (timestamps 4770-4772)
,I/LibraryLoader( 6448): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6448): Binding Chromium to main looper Looper (main, tid 1) {2f84b9cb}
,I/LibraryLoader( 6448): Expected native library version number "",actual native library version number ""
,I/chromium( 6448): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6448): Initializing chromium process, singleProcess=true
,W/art     ( 6448): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6448): ApplicationContext is null in ApplicationStatus
,W/chromium( 6448): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6448): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6448): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6448): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6448): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6448): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6448): Local Branch: 
I/Adreno-EGL( 6448): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6448): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6448):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 6448): Requires BLUETOOTH permission
,I/NSApplication( 6448): Starting up...
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6505): MountEmulatedStorage(),
E/Zygote  ( 6505): v2
I/libpersona( 6505): KNOX_SDCARD checking this for 10077
I/libpersona( 6505): KNOX_SDCARD not a persona,
I/SELinux ( 6505): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6505): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6505 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5823:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,E/SELinux ( 6505): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/art     (  308): Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 34.196ms,
,D/TimaKeyStoreProvider( 6505): TimaSignature is unavailable,
D/ActivityThread( 6505): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 21.654ms
,I/NetworkMonitor( 6231): type=WIFI subType= reason=null isConnected=true
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 20.366ms
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,W/libprocessgroup( 1017): failed to open /acct/uid_10148/pid_5823/cgroup.procs: No such file or directory
,D/WaitQueueForNetworkActivate( 6019): notifyNetworkActivated
,W/ContextImpl( 6019): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1017): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6019): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6019): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6019): exit::IDLE
D/InitializeManagerStateMachine( 6019): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6019): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6019): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6019): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6019): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6019): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6019): entry::SUCCESS
D/hcjo    ( 6019): AutoUpdateManager:INITCHECK:onInitializeSuccess
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1686): Starting #10
,I/Hs20UtilService( 1686): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
D/hcjo    ( 6019): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6019): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/InitializeManagerStateMachine( 6019): exit::SUCCESS
D/InitializeManagerStateMachine( 6019): entry::IDLE
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 1017): Killing 5841:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1686): Starting #11
,I/Hs20UtilService( 1686): Message received 5007
D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 1686): Starting #12
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,I/Hs20UtilService( 1686): Message received 5007
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE,
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,I/Hs20UtilService( 1686): Starting #13
,I/Hs20UtilService( 1686): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1017): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1017): mCursor = null
,D/ConnectivityService( 1017): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/PCWCLIENTTRACE_PushUtil( 5758): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5758): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5758): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5758): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1017): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
,I/splitIntent( 1017): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
,I/splitIntent( 1017): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6231): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  258): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1017): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,W/libprocessgroup( 1017): failed to open /acct/uid_10048/pid_5841/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6285): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6285): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6285): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6285): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SRIB_DCS( 1178): log_dcs ThreadedRenderer::initialize entered! 
,I/DBG_POLICYDM( 5800): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5800): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5800): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5800): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5800): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5800): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6300): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6300): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 3680): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sun Jan 17 13:14:06 GMT+01:00 2016
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3680): KLMSAbstractReciever(): onReceive().END.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3680): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3680): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3680): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3680): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3680): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3680): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3680): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3680): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.5.123: ( 3680): NetworkChangeOperations(): uploadRequestLog().END 
,I/DBG_POLICYDM( 5800): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3680): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3680): KLMSIntentService(): onDestroy()
,I/SA      ( 5945): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5945): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5945): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5800): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 5945): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/DBG_POLICYDM( 5800): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
I/SA      ( 5945): [OR] == isSIMCardReady false ==
,I/SA      ( 5945): [SCU] == networkStateCheck == true
,I/SA      ( 5945): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5945): isChinaCountryCode : false
I/SA      ( 5945): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5945): [OR] == networkStateCheck true ==
,E/DBG_POLICYDM( 5800): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 5945): [OR] GetMyCountryZoneTask
I/SA      ( 5945): [OR] onReceive END
,I/DBG_POLICYDM( 5800): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,V/DownloadManager( 1223): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/SA      ( 5945): [SRS] prepareGetMyCountryZone
,V/AlarmManager( 1017): waitForAlarm result :4
,D/accuweather( 1572): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,I/DBG_POLICYDM( 5800): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,D/daemonapp( 1620): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,I/DBG_POLICYDM( 5800): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5800): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5800): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,D/accuweather( 1572): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1572): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
I/DBG_POLICYDM( 5800): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,D/accuweather( 1572): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,I/DBG_POLICYDM( 5800): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/DBG_POLICYDM( 5800): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/accuweather( 1572): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,I/DBG_POLICYDM( 5800): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,D/SecContentProvider2( 1017): uri = 15 selection = getAppBlockDownloadState
I/DBG_POLICYDM( 5800): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/SecContentProvider2( 1017): mCursor = null
,I/SA      ( 5945): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5945): [SSP] query invoked
,E/DBG_POLICYDM( 5800): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/accuweather( 1572): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1572): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/QuickConnect( 6333): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5945): [TPMU] GetMccFromDB : null
I/SA      ( 5945): [SCU] getMccFromPreferece mcc = 260
I/QuickConnect( 6333): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6333): PeriphStartReceiver.onReceive - no need to start
,I/SA      ( 5945): [TPM] isNoProxy(default) : true
,I/DBG_POLICYDM( 5800): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5800): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,I/jxcore-log( 6131): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6131): 
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/File    ( 5945): fail readDirectory() errno=2
,I/jxcore-log( 6131): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6131): 
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecurityLogAgent( 6386): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6386): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6386): StateMachine : Current State = 1
D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecurityLogAgent( 6386): StateMachine : Changed Current State = 1
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/jxcore-log( 6131): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6131): 
,I/iu.Environment( 2002): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2002): num queued entries: 0
,I/jxcore-log( 6131): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6131): 
,I/iu.UploadsManager( 2002): num updated entries: 0
,I/iu.SyncManager( 2002): NEXT; no task
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2002): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 6131): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6131): 
,D/ChimeraCfgMgr( 2002): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/jxcore-log( 6131): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6131): 
,E/SPPClientService( 6427): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6427): [SystemStateMoniter] Current Time : 165850
E/SPPClientService( 6427): [SystemStateMoniter] No Connect : false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6019): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6019): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6019): exit::IDLE
D/InitializeManagerStateMachine( 6019): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6019): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6019): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6019): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6019): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6019): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6019): entry::SUCCESS
D/hcjo    ( 6019): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6019): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6019): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6019): exit::SUCCESS
D/InitializeManagerStateMachine( 6019): entry::IDLE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 6187): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6187): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6187): (HTTPLog)-Static: isShipBuild true
I/System.out( 6187): (HTTPLog)-Thread-1058-642012598: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6187): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10102
,I/System.out( 6187): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/art     ( 1719): Explicit concurrent mark sweep GC freed 23351(1351KB) AllocSpace objects, 5(101KB) LOS objects, 40% free, 7MB/12MB, paused 1.072ms total 43.528ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1719): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1719): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1719): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1719): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1719): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 6187): connection state changed from DISCONNECTED to CONNECTED
,D/GCM     ( 1719): Connected
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1719): Message class com.google.f.a.a.p
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/Kids    ( 2002): [AccountUtils] Account not ready
W/Kids    ( 2002): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2002): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2002): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2002): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2002): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2002): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2002): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2002): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2002): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2002): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2002): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2002): 	at java.lang.Thread.run(Thread.java:818)
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  292): DCD OFF
,I/SA      ( 5945): [RC New] Execute method=[GET] start
,I/SA      ( 5945): [RC New] Security=[true]
,I/System.out( 5945): Thread-1020(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5945): Thread-1020(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5945): Thread-1020(ApacheHTTPLog):isShipBuild true
I/System.out( 5945): Thread-1020(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5945): Thread-1020(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10036
,D/SSRM:n  ( 1017): SIOP:: AP = 320
,I/jxcore-log( 6131): Test app app.js loaded
I/jxcore-log( 6131): 
,I/Choreographer( 6131): Skipped 316 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6131): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4312, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2654): Disconnected process message: 10
,E/SQLiteLog( 1719): (10) POSIX Error : 11 SQLite Error : 3850
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,D/ConnectivityService( 1017): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524295
,V/AlarmManager( 1017): waitForAlarm result :4
,I/SA      ( 5945): [RC New] [v2liruge] api execute + 651
I/SA      ( 5945): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5945): AsyncTask #1 calls detatch()
,I/SA      ( 5945): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5945): [OCP] update openData : PL
,I/SA      ( 5945): [TPMU] getNetworkMcc : 
,I/SA      ( 5945): [SCU] saveMccToPreferece Start
I/SA      ( 5945): [SCU] RegionMCC : 260
I/SA      ( 5945): [SSP] query invoked
,I/SA      ( 5945): [TPMU] GetMccFromDB : null
I/SA      ( 5945): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5945): [SCU] saveMccToPreferece End
,I/SA      ( 5945): [RC New] executeRequest [v2liruge] end. 721
,I/SA      ( 5945): [RC New] Execute end
I/SA      ( 5945): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5945): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 6255): wlan0: sending IPv6 Router Solicitation
,V/GLSActivity( 1719): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1719): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1719): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1719): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1719): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1719): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5341): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5341): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5341): [1] 5.onFinished: Scheduling replication attempt 5.
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6231): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6231): Stop autocaching.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WearableService( 4821): callingUid 10011, callindPid: 4821
,E/GmsUtils( 6231): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6231): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/Watchdog( 1017): !@Sync 5
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  258): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  258): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 1017): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1017) eventTime = 168906
D/PowerManagerService( 1017): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017 (0x0)
,D/PowerManagerService( 1017): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1017, ws=WorkSource{10049}) (elapsedTime=3486)
,E/SMD     (  292): DCD OFF
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5758): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5758): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5758): [GetString-S],
I/ReactiveServiceManager( 5758): Supported : 1
,D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1017): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1017): QSEECom_shutdown_app, app_id = 11
E/terrier ( 1017): handleString: Failed to handle string(-4)
E/terrier ( 1017): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 5758): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5758): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5758): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5758): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5758): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5758): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 6255): wlan0: sending IPv6 Router Solicitation
,I/PowerManagerService( 1017): [PWL] Off : 75s ago
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1719): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1719): Vacuum at: now=1453032853920 tag=VacuumService
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 41054(2MB) AllocSpace objects, 5(84KB) LOS objects, 33% free, 23MB/35MB, paused 2.517ms total 153.576ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Batterystats( 2002): User is not opted-in to Usage & Diagnostics.
,I/dhcpcd  ( 6255): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6255): wlan0: no IPv6 Routers available
,E/SMD     (  292): DCD OFF
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6019): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6019): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6019): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6019): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6019): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6019): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6019): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6019): entry::IDLE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6019): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6019): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6019): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6019): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6019): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 6019): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6019): entry::IDLE
,D/SSRM:n  ( 1017): SIOP:: AP = 300
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1017): waitForAlarm result :4
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager( 1017): waitForAlarm result :4
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,V/GLSActivity( 1719): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1719): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1719): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1719): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1719): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1719): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5341): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5341): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5341): [1] 5.onFinished: Giving up after 6 failures.
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 6
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 105s ago
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :4
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/Watchdog( 1017): !@Sync 7
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
D/SSRM:n  ( 1017): SIOP:: AP = 270
,I/PowerManagerService( 1017): [PWL] Off : 140s ago,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1017): Plugged,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2654): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 8
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  292): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1017): [PWL] Off : 180s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/Watchdog( 1017): !@Sync 9
,E/SMD     (  292): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6046): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6046): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1719): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1719): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1719): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1719): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1719): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1719): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1719): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1719): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1719): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1719): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6046): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6046): Soft error
E/BooksSync( 6046): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6046): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6046): Sync error
E/BooksSync( 6046): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6046): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6046): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 289514, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,I/jxcore-log( 6131): TAP version 13
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup,
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # basic
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 1 sane
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # another
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 2 sane
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 3 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 4 null
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 5 (unnamed assert)
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 6 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 7 should not throw
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 8 (unnamed assert)
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 9 (unnamed assert)
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 10 should not throw
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 11 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 12 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 13 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # failed to get mobile documents path
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 14 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 15 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 16 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 17 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # #init should register the networkChanged event
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 18 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # #startBroadcasting should throw on null device name
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 19 should throw
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 20 should throw
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # #startBroadcasting should throw on non-number port
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 21 should throw
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # #startBroadcasting should throw on NaN port
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 22 should throw
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # #startBroadcasting should throw on negative port
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 23 should throw
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # #startBroadcasting should throw on too large port,
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 24 should throw
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 25 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 26 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 27 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 28 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 29 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 30 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 31 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 32 should be equal,
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup,
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 33 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 34 should be equal,
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup,
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 35 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 36 should be equal
I/jxcore-log( 6131): ,
I/jxcore-log( 6131): ok 37 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 38 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 39 should be equal
,I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,E/SMD     (  292): DCD OFF,
,I/jxcore-log( 6131): # should call Mobile("Disconnect") without an error
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 40 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 41 should be equal,
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 42 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 43 should be equal,
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032994952.6131,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): initialize: My bluetooth address is 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032994952.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6131): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6131): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,D/BluetoothSocket( 6131): bindListen(), new LocalSocket 
,D/BluetoothSocket( 6131): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6131): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2493802d
,D/BluetoothSocket( 6131): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: OK
I/io.jxcore.node.ConnectionHelper( 6131): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032994952.6131
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): createAdvertiseData: From: 1453032994952.6131 b6a44ad1-d319-4b3a-815d-8b805a47fb51 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): 8:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 8, -20, -87, 80, 117, 65]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6131): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=3517633a-614a-4901-8b68-d6d200496685
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=3517633a-614a-4901-8b68-d6d200496685, clientIf=6
,D/BluetoothLeAdvertiser( 6131): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2654): message : 0
,D/BtGatt.AdvertiseManager( 2654): number of adv instance running0
,D/BtGatt.AdvertiseManager( 2654): size of list is =0
,D/BtGatt.AdvertiseManager( 2654): starting advertising
,D/BtGatt.AdvertiseManager( 2654): isStandardAdvfalse
,D/BtGatt.GattService( 2654): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): starting multi advertising
,D/BtGatt.GattService( 2654): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager( 2654): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=f0d8bceb-457d-4380-93ca-fb64046e0642
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=f0d8bceb-457d-4380-93ca-fb64046e0642, clientIf=7
D/BluetoothLeScanner( 6131): onClientRegistered() - status=0 clientIf=7
D/BtGatt.GattService( 2654): start scan with filters
D/BtGatt.ScanManager( 2654): handling starting scan
,D/BluetoothAdapterService( 2654): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35d30385
,D/BtGatt.GattService( 2654): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): allow scan with filters
D/BtGatt.ScanManager( 2654): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager( 2654): set filter index= 3 for clientIf= 7
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 2654): :scan window =2000 Scan interval = 5000
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startBlePeerDiscovery: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032994952.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): start: {"pi":"08:EC:A9:50:75:41","pn":"1453032994952.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"1453032994952.6131","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1017): InactiveState{ what=139292 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 1017): P2pEnabledState add service
,D/WifiP2pService( 1017): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 6131): start: OK
,I/jxcore-log( 6131): ok 44 Should be able to call startBroadcasting without error
I/jxcore-log( 6131): 
I/io.jxcore.node.ConnectionHelper( 6131): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): shutdown
D/BluetoothSocket( 6131): close() in, this: android.bluetooth.BluetoothSocket@2c29c9ae, channel: 6, state: LISTENING
,D/BluetoothSocket( 6131): close() this: android.bluetooth.BluetoothSocket@2c29c9ae, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2493802d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@33d2134fmSocket: android.net.LocalSocket@106e7adc impl:android.net.LocalSocketImpl@aa187e5 fd:FileDescriptor[106]
D/BluetoothSocket( 6131): Closing mSocket: android.net.LocalSocket@106e7adc impl:android.net.LocalSocketImpl@aa187e5 fd:FileDescriptor[106]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 2654): message : 1
,D/BtGatt.AdvertiseManager( 2654): stop advertise for client 6
D/BtGatt.AdvertiseManager( 2654):  standardAdvClientIf = 0client.clientIf6
D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: -1,
D/WifiP2pService( 1017): InactiveState{ what=139265 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): onServerStopped
,D/BtGatt.GattService( 2654): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2654): Client app is not null!
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1381): USE_NETWORK : USE_NETWORK OFF,
D/BtGatt.GattService( 2654): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: false
,D/WifiP2pService( 1017): discovery change broadcast true
,D/BtGatt.GattService( 2654): stopScan() - queue size =1
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=7
,D/BtGatt.ScanManager( 2654): filter size is 1
D/BtGatt.ScanManager( 2654): delete FilterIndex - 3
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsBlePeerDiscoveryStartedChanged: true
D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 2654): stop scan,
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue emtpy, scan stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): stop: Stopping services,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): stop: Stopping P2P device discovery...
D/WifiP2pService( 1017): InactiveState{ what=139298 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: NOT_INITIALIZED
D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService( 1017): P2pEnabledState clear service,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopWifiPeerDiscovery: Stopped
D/WifiP2pService( 1017): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): release: No more listeners, de-initializing...
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
I/wpa_supplicant( 1381): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: NOT_STARTED
D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState clear service request
,I/jxcore-log( 6131): ok 45 Should be able to call stopBroadcasting without error
I/jxcore-log( 6131): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032995219.6131
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): initialize: My bluetooth address is 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032995219.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6131): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6131): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,D/BluetoothSocket( 6131): bindListen(), new LocalSocket 
D/BluetoothSocket( 6131): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6131): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@24c6956b
D/BluetoothSocket( 6131): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: OK
I/io.jxcore.node.ConnectionHelper( 6131): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032995219.6131
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): createAdvertiseData: From: 1453032995219.6131 b6a44ad1-d319-4b3a-815d-8b805a47fb51 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): 8:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 8, -20, -87, 80, 117, 65]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6131): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=72e78447-2327-4a93-9f4a-c7977296372e
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=72e78447-2327-4a93-9f4a-c7977296372e, clientIf=6
,D/BluetoothLeAdvertiser( 6131): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2654): message : 0
,D/BtGatt.AdvertiseManager( 2654): number of adv instance running0
,D/BtGatt.AdvertiseManager( 2654): size of list is =0
,D/BtGatt.AdvertiseManager( 2654): starting advertising
,D/BtGatt.AdvertiseManager( 2654): isStandardAdvfalse
,D/BtGatt.GattService( 2654): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): starting multi advertising
,D/BtGatt.GattService( 2654): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager( 2654): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=c98e56e8-560b-43cd-9001-fadd567f1f6a
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=c98e56e8-560b-43cd-9001-fadd567f1f6a, clientIf=7
,D/BluetoothLeScanner( 6131): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 2654): start scan with filters
,D/BtGatt.ScanManager( 2654): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startBlePeerDiscovery: OK
,D/BtGatt.GattService( 2654): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): allow scan with filters
D/BtGatt.ScanManager( 2654): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager( 2654): set filter index= 4 for clientIf= 7
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager( 2654): :scan window =2000 Scan interval = 5000
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032995219.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): start: {"pi":"08:EC:A9:50:75:41","pn":"1453032995219.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"1453032995219.6131","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1017): InactiveState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: INITIALIZED
D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): start: Starting P2P device discovery...
D/WifiP2pService( 1017): P2pEnabledState add service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: true,
D/WifiP2pService( 1017): add a new client
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService( 1017): InactiveState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: OK
D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: RUNNING_BLE_AND_WIFI
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/io.jxcore.node.ConnectionHelper( 6131): start: OK
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/jxcore-log( 6131): ok 46 Should be able to call startBroadcasting without error
I/jxcore-log( 6131): 
I/wpa_supplicant( 1381): USE_NETWORK : USE_NETWORK OFF
I/io.jxcore.node.ConnectionHelper( 6131): stop
I/wpa_supplicant( 1381): p2p0: P2P: Reject scan trigger since one is already pending
D/WifiP2pService( 1017): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): shutdown
D/BluetoothSocket( 6131): close() in, this: android.bluetooth.BluetoothSocket@1c4d4974, channel: 6, state: LISTENING
D/BluetoothSocket( 6131): close() this: android.bluetooth.BluetoothSocket@1c4d4974, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@24c6956b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1d01ce9dmSocket: android.net.LocalSocket@1126ff12 impl:android.net.LocalSocketImpl@93e46e3 fd:FileDescriptor[106]
D/BluetoothSocket( 6131): Closing mSocket: android.net.LocalSocket@1126ff12 impl:android.net.LocalSocketImpl@93e46e3 fd:FileDescriptor[106]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): onServerStopped
,D/BtGatt.AdvertiseManager( 2654): message : 1
,D/BtGatt.AdvertiseManager( 2654): stop advertise for client 6
D/BtGatt.AdvertiseManager( 2654):  standardAdvClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: -1
,D/BtGatt.GattService( 2654): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2654): Client app is not null!
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2654): stopScan() - queue size =1
,D/BtGatt.ScanManager( 2654): filter size is 1
,D/BtGatt.ScanManager( 2654): delete FilterIndex - 4
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=7
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): stop scan
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue emtpy, scan stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsBlePeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): stop: Stopping P2P device discovery...
,D/WifiP2pService( 1017): InactiveState{ what=139298 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
D/WifiP2pService( 1017): P2pEnabledState clear service
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService( 1017): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): release: No more listeners, de-initializing...
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
I/wpa_supplicant( 1381): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: No more listeners, de-initializing...
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: NOT_STARTED
,D/WifiP2pService( 1017): P2pEnabledState clear service request
D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1017): discovery change broadcast false
,I/jxcore-log( 6131): ok 47 Should be able to call stopBroadcasting without error
I/jxcore-log( 6131): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032995420.6131
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): initialize: My bluetooth address is 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032995420.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6131): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6131): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,D/BluetoothSocket( 6131): bindListen(), new LocalSocket 
D/BluetoothSocket( 6131): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket( 6131): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36b1b799
D/BluetoothSocket( 6131): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: OK
I/io.jxcore.node.ConnectionHelper( 6131): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032995420.6131
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): createAdvertiseData: From: 1453032995420.6131 b6a44ad1-d319-4b3a-815d-8b805a47fb51 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): 8:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 8, -20, -87, 80, 117, 65]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6131): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=cf809760-5fed-4290-80ca-5df935c6eec2
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=cf809760-5fed-4290-80ca-5df935c6eec2, clientIf=6
,D/BluetoothLeAdvertiser( 6131): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2654): message : 0
,D/BtGatt.AdvertiseManager( 2654): number of adv instance running0
,D/BtGatt.AdvertiseManager( 2654): size of list is =0
,D/BtGatt.AdvertiseManager( 2654): starting advertising
,D/BtGatt.AdvertiseManager( 2654): isStandardAdvfalse
,D/BtGatt.GattService( 2654): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): starting multi advertising
,D/BtGatt.GattService( 2654): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager( 2654): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=3151d7ca-131d-4d9b-9899-2cc612e4518e
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=3151d7ca-131d-4d9b-9899-2cc612e4518e, clientIf=7
,D/BluetoothLeScanner( 6131): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 2654): start scan with filters
,D/BtGatt.ScanManager( 2654): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startBlePeerDiscovery: OK
,D/BtGatt.GattService( 2654): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1,
D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): allow scan with filters
D/BtGatt.ScanManager( 2654): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager( 2654): set filter index= 5 for clientIf= 7
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 2654): :scan window =2000 Scan interval = 5000
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032995420.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): start: {"pi":"08:EC:A9:50:75:41","pn":"1453032995420.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"1453032995420.6131","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1017): InactiveState{ what=139292 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
D/WifiP2pService( 1017): P2pEnabledState add service
,D/WifiP2pService( 1017): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6131): start: OK
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1381): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1381): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 6131): ok 48 Should be able to call startBroadcasting without error
I/jxcore-log( 6131): 
,D/WifiP2pService( 1017): discovery change broadcast true
,I/io.jxcore.node.ConnectionHelper( 6131): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): shutdown
D/BluetoothSocket( 6131): close() in, this: android.bluetooth.BluetoothSocket@3bdf5e6a, channel: 6, state: LISTENING
D/BluetoothSocket( 6131): close() this: android.bluetooth.BluetoothSocket@3bdf5e6a, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36b1b799, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3cdbaf5bmSocket: android.net.LocalSocket@145993f8 impl:android.net.LocalSocketImpl@1f09c0d1 fd:FileDescriptor[106]
D/BluetoothSocket( 6131): Closing mSocket: android.net.LocalSocket@145993f8 impl:android.net.LocalSocketImpl@1f09c0d1 fd:FileDescriptor[106]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): onServerStopped
,D/BtGatt.AdvertiseManager( 2654): message : 1
,D/BtGatt.AdvertiseManager( 2654): stop advertise for client 6
,D/BtGatt.AdvertiseManager( 2654):  standardAdvClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: -1
,D/BtGatt.GattService( 2654): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2654): Client app is not null!
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2654): stopScan() - queue size =1
,D/BtGatt.ScanManager( 2654): filter size is 1
,D/BtGatt.ScanManager( 2654): delete FilterIndex - 5
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=7
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 2654): stop scan
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsScannerStartedChanged: false
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): stop: Stopping services
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue emtpy, scan stopped
,D/WifiP2pService( 1017): InactiveState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): release: No more listeners, de-initializing...
D/WifiP2pService( 1017): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: NOT_STARTED,
D/WifiP2pService( 1017): remove client information from framework
I/jxcore-log( 6131): ok 49 Should be able to call stopBroadcasting without error
I/jxcore-log( 6131): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
I/wpa_supplicant( 1381): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState clear service request
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1017): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032995615.6131
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): initialize: My bluetooth address is 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032995615.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6131): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6131): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,D/BluetoothSocket( 6131): bindListen(), new LocalSocket 
D/BluetoothSocket( 6131): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket( 6131): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@131be637
D/BluetoothSocket( 6131): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: OK
,I/io.jxcore.node.ConnectionHelper( 6131): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032995615.6131
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): createAdvertiseData: From: 1453032995615.6131 b6a44ad1-d319-4b3a-815d-8b805a47fb51 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): 8:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 8, -20, -87, 80, 117, 65]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6131): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=509adab6-8141-4501-b62a-54ea6974baa2
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=509adab6-8141-4501-b62a-54ea6974baa2, clientIf=6
,D/BluetoothLeAdvertiser( 6131): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2654): message : 0
,D/BtGatt.AdvertiseManager( 2654): number of adv instance running0
D/BtGatt.AdvertiseManager( 2654): size of list is =0
,D/BtGatt.AdvertiseManager( 2654): starting advertising
,D/BtGatt.AdvertiseManager( 2654): isStandardAdvfalse
,D/BtGatt.GattService( 2654): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): starting multi advertising
,D/BtGatt.GattService( 2654): onAdvertiseDataSet() - clientIf=6, status=0,
D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: 0
D/BtGatt.AdvertiseManager( 2654): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=8a6876ee-8323-40a0-ab1b-4d3638d69755
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=8a6876ee-8323-40a0-ab1b-4d3638d69755, clientIf=7
,D/BluetoothLeScanner( 6131): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 2654): start scan with filters
,D/BtGatt.ScanManager( 2654): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startBlePeerDiscovery: OK
,D/BtGatt.GattService( 2654): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): allow scan with filters
,D/BtGatt.ScanManager( 2654): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager( 2654): set filter index= 6 for clientIf= 7
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 2654): :scan window =2000 Scan interval = 5000
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032995615.6131","ra":"08:EC:A9:50:75:41"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): start: {"pi":"08:EC:A9:50:75:41","pn":"1453032995615.6131","ra":"08:EC:A9:50:75:41"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"1453032995615.6131","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1017): InactiveState{ what=139292 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
D/WifiP2pService( 1017): P2pEnabledState add service
,D/WifiP2pService( 1017): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startWifiPeerDiscovery: Wi-Fi Direct OK
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: OK
D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: RUNNING_BLE_AND_WIFI
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/io.jxcore.node.ConnectionHelper( 6131): start: OK
D/WifiP2pService( 1017): discovery change broadcast true
I/jxcore-log( 6131): ok 50 Should be able to call startBroadcasting without error
I/jxcore-log( 6131): 
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1381): USE_NETWORK : USE_NETWORK OFF
I/io.jxcore.node.ConnectionHelper( 6131): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): shutdown
D/BluetoothSocket( 6131): close() in, this: android.bluetooth.BluetoothSocket@39a6ea10, channel: 6, state: LISTENING
D/BluetoothSocket( 6131): close() this: android.bluetooth.BluetoothSocket@39a6ea10, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@131be637, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3fc2b909mSocket: android.net.LocalSocket@203fb70e impl:android.net.LocalSocketImpl@7bb652f fd:FileDescriptor[106]
,D/BluetoothSocket( 6131): Closing mSocket: android.net.LocalSocket@203fb70e impl:android.net.LocalSocketImpl@7bb652f fd:FileDescriptor[106]
I/wpa_supplicant( 1381): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): onServerStopped
D/BtGatt.AdvertiseManager( 2654): message : 1
,D/BtGatt.AdvertiseManager( 2654): stop advertise for client 6
D/BtGatt.AdvertiseManager( 2654):  standardAdvClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: -1
,D/BtGatt.GattService( 2654): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2654): Client app is not null!
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2654): stopScan() - queue size =1
,D/BtGatt.ScanManager( 2654): filter size is 1
,D/BtGatt.ScanManager( 2654): delete FilterIndex - 6
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=7
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): stop scan
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue emtpy, scan stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): stop: Stopping P2P device discovery...
D/WifiP2pService( 1017): InactiveState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: NOT_INITIALIZED
D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: NOT_STARTED
D/WifiP2pService( 1017): P2pEnabledState clear service
I/jxcore-log( 6131): ok 51 Should be able to call stopBroadcasting without error
I/jxcore-log( 6131): 
D/WifiP2pService( 1017): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/WifiP2pService( 1017): InactiveState{ what=139268 }
I/wpa_supplicant( 1381): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032995807.6131
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): initialize: My bluetooth address is 08:EC:A9:50:75:41
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/WifiP2pService( 1017): InactiveState{ what=147493 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032995807.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6131): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6131): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,D/BluetoothSocket( 6131): bindListen(), new LocalSocket 
D/BluetoothSocket( 6131): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket( 6131): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2054dcc5
D/BluetoothSocket( 6131): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: OK
,I/io.jxcore.node.ConnectionHelper( 6131): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032995807.6131
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): createAdvertiseData: From: 1453032995807.6131 b6a44ad1-d319-4b3a-815d-8b805a47fb51 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): 8:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 8, -20, -87, 80, 117, 65]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6131): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=508dc59b-4fbc-4945-b1c9-68c1cbe1a84f
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=508dc59b-4fbc-4945-b1c9-68c1cbe1a84f, clientIf=6
,D/BluetoothLeAdvertiser( 6131): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2654): message : 0
,D/BtGatt.AdvertiseManager( 2654): number of adv instance running0
,D/BtGatt.AdvertiseManager( 2654): size of list is =0
,D/BtGatt.AdvertiseManager( 2654): starting advertising
,D/BtGatt.AdvertiseManager( 2654): isStandardAdvfalse
,D/BtGatt.GattService( 2654): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): starting multi advertising
,D/BtGatt.GattService( 2654): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager( 2654): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=191c0eac-c378-404d-8a62-7b2ce0530c35,
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=191c0eac-c378-404d-8a62-7b2ce0530c35, clientIf=7,
D/BluetoothLeScanner( 6131): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 2654): start scan with filters,
D/BtGatt.ScanManager( 2654): handling starting scan,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startBlePeerDiscovery: OK
D/BtGatt.GattService( 2654): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0,
D/BtGatt.ScanManager( 2654): allow scan with filters
D/BtGatt.ScanManager( 2654): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager( 2654): set filter index= 7 for clientIf= 7,
D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15,
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager( 2654): :scan window =2000 Scan interval = 5000
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032995807.6131","ra":"08:EC:A9:50:75:41"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): start: {"pi":"08:EC:A9:50:75:41","pn":"1453032995807.6131","ra":"08:EC:A9:50:75:41"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"1453032995807.6131","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1017): InactiveState{ what=139292 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
D/WifiP2pService( 1017): P2pEnabledState add service
,D/WifiP2pService( 1017): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6131): start: OK
,I/jxcore-log( 6131): ok 52 Should be able to call startBroadcasting without error
I/jxcore-log( 6131): 
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1381): USE_NETWORK : USE_NETWORK OFF
,I/io.jxcore.node.ConnectionHelper( 6131): stop
I/wpa_supplicant( 1381): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): shutdown
,D/BluetoothSocket( 6131): close() in, this: android.bluetooth.BluetoothSocket@edf99e6, channel: 6, state: LISTENING
,D/BluetoothSocket( 6131): close() this: android.bluetooth.BluetoothSocket@edf99e6, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2054dcc5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@23fccb27mSocket: android.net.LocalSocket@1fb291d4 impl:android.net.LocalSocketImpl@56edf7d fd:FileDescriptor[106]
D/WifiP2pService( 1017): discovery change broadcast true,
D/BluetoothSocket( 6131): Closing mSocket: android.net.LocalSocket@1fb291d4 impl:android.net.LocalSocketImpl@56edf7d fd:FileDescriptor[106]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 2654): message : 1
,D/BtGatt.AdvertiseManager( 2654): stop advertise for client 6
,D/BtGatt.AdvertiseManager( 2654):  standardAdvClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: -1
,D/BtGatt.GattService( 2654): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2654): Client app is not null!
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2654): stopScan() - queue size =1
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=7
,D/BtGatt.ScanManager( 2654): filter size is 1
,D/BtGatt.ScanManager( 2654): delete FilterIndex - 7
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): stop scan
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue emtpy, scan stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsBlePeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): stop: Stopping services
,D/WifiP2pService( 1017): InactiveState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: NOT_STARTED
,D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
,D/WifiP2pService( 1017): P2pEnabledState clear service
I/jxcore-log( 6131): ok 53 Should be able to call stopBroadcasting without error
I/jxcore-log( 6131): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032996012.6131
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
,D/WifiP2pService( 1017): remove client information from framework
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/wpa_supplicant( 1381): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): initialize: My bluetooth address is 08:EC:A9:50:75:41
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032996012.6131","ra":"08:EC:A9:50:75:41"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6131): getBluetoothService() called with no BluetoothManagerCallback
,D/WifiP2pService( 1017): P2pEnabledState clear service request
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
,D/BluetoothSocket( 6131): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,D/BluetoothSocket( 6131): bindListen(), new LocalSocket 
D/BluetoothSocket( 6131): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket( 6131): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27e0f2c3
D/BluetoothSocket( 6131): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: OK
I/io.jxcore.node.ConnectionHelper( 6131): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032996012.6131
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): createAdvertiseData: From: 1453032996012.6131 b6a44ad1-d319-4b3a-815d-8b805a47fb51 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): 8:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 8, -20, -87, 80, 117, 65]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6131): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BtGatt.GattService( 2654): registerClient() - UUID=bffce8be-5fc0-4000-aaf8-d6c8e7504a6c
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=bffce8be-5fc0-4000-aaf8-d6c8e7504a6c, clientIf=6
,D/BluetoothLeAdvertiser( 6131): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2654): message : 0
,D/BtGatt.AdvertiseManager( 2654): number of adv instance running0
,D/BtGatt.AdvertiseManager( 2654): size of list is =0
,D/BtGatt.AdvertiseManager( 2654): starting advertising
,D/BtGatt.AdvertiseManager( 2654): isStandardAdvfalse
,D/BtGatt.GattService( 2654): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): starting multi advertising
,D/BtGatt.GattService( 2654): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager( 2654): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=2b1f726f-79af-4fba-9539-98baf5a4daaa
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=2b1f726f-79af-4fba-9539-98baf5a4daaa, clientIf=7
,D/BluetoothLeScanner( 6131): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 2654): start scan with filters
,D/BtGatt.ScanManager( 2654): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startBlePeerDiscovery: OK
,D/BtGatt.GattService( 2654): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): allow scan with filters
D/BtGatt.ScanManager( 2654): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager( 2654): set filter index= 8 for clientIf= 7
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager( 2654): :scan window =2000 Scan interval = 5000
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032996012.6131","ra":"08:EC:A9:50:75:41"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): start: {"pi":"08:EC:A9:50:75:41","pn":"1453032996012.6131","ra":"08:EC:A9:50:75:41"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"1453032996012.6131","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1017): InactiveState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6131): start: OK
,D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
,I/jxcore-log( 6131): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 6131): 
,I/io.jxcore.node.ConnectionHelper( 6131): stop,
D/WifiP2pService( 1017): P2pEnabledState add service,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): shutdown
D/BluetoothSocket( 6131): close() in, this: android.bluetooth.BluetoothSocket@2e476c, channel: 6, state: LISTENING
D/BluetoothSocket( 6131): close() this: android.bluetooth.BluetoothSocket@2e476c, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27e0f2c3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@16ff8135mSocket: android.net.LocalSocket@82659ca impl:android.net.LocalSocketImpl@23ebf73b fd:FileDescriptor[106]
D/WifiP2pService( 1017): add a new client
D/BluetoothSocket( 6131): Closing mSocket: android.net.LocalSocket@82659ca impl:android.net.LocalSocketImpl@23ebf73b fd:FileDescriptor[106]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): onServerStopped
D/BtGatt.AdvertiseManager( 2654): message : 1
,D/BtGatt.AdvertiseManager( 2654): stop advertise for client 6
D/BtGatt.AdvertiseManager( 2654):  standardAdvClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: -1
,D/BtGatt.GattService( 2654): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2654): Client app is not null!
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1381): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1381): p2p0: P2P: Reject scan trigger since one is already pending
,D/WifiP2pService( 1017): discovery change broadcast true
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2654): stopScan() - queue size =1
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=7
,D/BtGatt.ScanManager( 2654): filter size is 1
,D/BtGatt.ScanManager( 2654): delete FilterIndex - 8
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): stop scan
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue emtpy, scan stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): stop: Stopping services
,D/WifiP2pService( 1017): InactiveState{ what=139298 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
D/WifiP2pService( 1017): P2pEnabledState clear service
,D/WifiP2pService( 1017): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: NOT_STARTED
D/WifiP2pService( 1017): InactiveState{ what=139268 }
I/wpa_supplicant( 1381): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
I/jxcore-log( 6131): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 6131): 
D/WifiP2pService( 1017): P2pEnabledState clear service request
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032996221.6131
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): initialize: My bluetooth address is 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032996221.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6131): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6131): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,D/BluetoothSocket( 6131): bindListen(), new LocalSocket 
D/BluetoothSocket( 6131): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket( 6131): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2bb3fbb1
D/BluetoothSocket( 6131): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: OK
I/io.jxcore.node.ConnectionHelper( 6131): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032996221.6131
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): createAdvertiseData: From: 1453032996221.6131 b6a44ad1-d319-4b3a-815d-8b805a47fb51 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): 8:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 8, -20, -87, 80, 117, 65]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6131): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Waiting for incoming connections...
,D/BtGatt.GattService( 2654): registerClient() - UUID=088523fe-7a64-42ac-b14b-e56b07aabfd0,
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=088523fe-7a64-42ac-b14b-e56b07aabfd0, clientIf=6
,D/BluetoothLeAdvertiser( 6131): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2654): message : 0
,D/BtGatt.AdvertiseManager( 2654): number of adv instance running0
,D/BtGatt.AdvertiseManager( 2654): size of list is =0
,D/BtGatt.AdvertiseManager( 2654): starting advertising
,D/BtGatt.AdvertiseManager( 2654): isStandardAdvfalse
,D/BtGatt.GattService( 2654): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): starting multi advertising
,D/BtGatt.GattService( 2654): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager( 2654): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=73c3c394-3dc8-4e91-84e8-32f504f78dae
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=73c3c394-3dc8-4e91-84e8-32f504f78dae, clientIf=7
,D/BluetoothLeScanner( 6131): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 2654): start scan with filters
,D/BtGatt.ScanManager( 2654): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startBlePeerDiscovery: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032996221.6131","ra":"08:EC:A9:50:75:41"}
,D/BtGatt.GattService( 2654): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 2654): allow scan with filters
D/BtGatt.ScanManager( 2654): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager( 2654): set filter index= 9 for clientIf= 7
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): start: {"pi":"08:EC:A9:50:75:41","pn":"1453032996221.6131","ra":"08:EC:A9:50:75:41"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"1453032996221.6131","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 2654): :scan window =2000 Scan interval = 5000
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: INITIALIZED
D/WifiP2pService( 1017): InactiveState{ what=139292 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): start: Starting P2P device discovery...
D/WifiP2pService( 1017): P2pEnabledState add service
,D/WifiP2pService( 1017): add a new client,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6131): start: OK,
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,I/jxcore-log( 6131): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 6131): 
D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1381): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1017): discovery change broadcast true
,I/io.jxcore.node.ConnectionHelper( 6131): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): shutdown
D/BluetoothSocket( 6131): close() in, this: android.bluetooth.BluetoothSocket@1ba85822, channel: 6, state: LISTENING
D/BluetoothSocket( 6131): close() this: android.bluetooth.BluetoothSocket@1ba85822, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2bb3fbb1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1dd412b3mSocket: android.net.LocalSocket@3a70b070 impl:android.net.LocalSocketImpl@1e5d6fe9 fd:FileDescriptor[106]
D/BluetoothSocket( 6131): Closing mSocket: android.net.LocalSocket@3a70b070 impl:android.net.LocalSocketImpl@1e5d6fe9 fd:FileDescriptor[106]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): onServerStopped
,D/BtGatt.AdvertiseManager( 2654): message : 1
,D/BtGatt.AdvertiseManager( 2654): stop advertise for client 6
,D/BtGatt.AdvertiseManager( 2654):  standardAdvClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: -1
,D/BtGatt.GattService( 2654): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2654): Client app is not null!
,E/bt-btif ( 2654): property type:241, len:0 is invalid
,E/        ( 2654): ### ASSERT : external/bluetooth/bluedroid/main/../btif/src/btif_dm.c line 4560 failed to save remote device manufacturer (1) ###
,E/BluetoothRemoteDevices( 2654): devicePropertyChangedCallback: bdDevice: 88:C6:26:19:97:DC, value is empty for type: 241
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: false
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.CLASS_CHANGED
,D/BtGatt.GattService( 2654): stopScan() - queue size =1
D/ScanRecord( 2654): parseFromBytes
D/ScanRecord( 2654): first manudata for manu ID
,D/BtGatt.GattService( 2654): result: ScanResult{mDevice=88:C6:26:19:97:DC, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=[72daa6c3-29c2-6283-0c4a-2818e4d37e75], mManufacturerSpecificData={50824=[38, 25, -105, -36]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=��], mRssi=-88, mTimestampNanos=315041448940}
D/BtGatt.ScanManager( 2654): filter size is 1
D/BtGatt.ScanManager( 2654): delete FilterIndex - 9
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=7
D/BtGatt.GattService( 2654): filter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
,W/MessageQueue( 2654): Handler (com.android.bluetooth.gatt.ContextMap$App$1) {3f94b1af} sending message to a Handler on a dead thread
W/MessageQueue( 2654): java.lang.IllegalStateException: Handler (com.android.bluetooth.gatt.ContextMap$App$1) {3f94b1af} sending message to a Handler on a dead thread
W/MessageQueue( 2654): 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
W/MessageQueue( 2654): 	at android.os.Handler.enqueueMessage(Handler.java:631)
W/MessageQueue( 2654): 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
W/MessageQueue( 2654): 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
W/MessageQueue( 2654): 	at android.os.Handler.sendMessage(Handler.java:507)
W/MessageQueue( 2654): 	at com.android.bluetooth.gatt.GattService.onScanResult(GattService.java:624)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsBlePeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): stop: Stopping services
D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 2654): stop scan
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): stop: Stopping P2P device discovery...
D/WifiP2pService( 1017): InactiveState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: NOT_INITIALIZED
D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService( 1017): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: NOT_STARTED
,I/jxcore-log( 6131): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 6131): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032996483.6131
D/WifiP2pService( 1017): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
I/wpa_supplicant( 1381): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): initialize: My bluetooth address is 08:EC:A9:50:75:41,
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032996483.6131","ra":"08:EC:A9:50:75:41"},
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6131): getBluetoothService() called with no BluetoothManagerCallback,
,D/BluetoothSocket( 6131): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,D/BluetoothSocket( 6131): bindListen(), new LocalSocket 
D/BluetoothSocket( 6131): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6131): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@20f3270f
D/BluetoothSocket( 6131): channel: 6,
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: OK
,I/io.jxcore.node.ConnectionHelper( 6131): start: Using peer discovery mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032996483.6131
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): createAdvertiseData: From: 1453032996483.6131 b6a44ad1-d319-4b3a-815d-8b805a47fb51 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): 8:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 8, -20, -87, 80, 117, 65]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6131): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/WifiP2pService( 1017): InactiveState{ what=147493 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
,D/BtGatt.GattService( 2654): registerClient() - UUID=073ef810-0e26-475d-8fb5-df4f28bc4882
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=073ef810-0e26-475d-8fb5-df4f28bc4882, clientIf=6
,D/BluetoothLeAdvertiser( 6131): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2654): message : 0
,D/BtGatt.AdvertiseManager( 2654): number of adv instance running0
,D/BtGatt.AdvertiseManager( 2654): size of list is =0
,D/BtGatt.AdvertiseManager( 2654): starting advertising
,D/BtGatt.AdvertiseManager( 2654): isStandardAdvfalse
,D/BtGatt.GattService( 2654): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): starting multi advertising
,D/BtGatt.GattService( 2654): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager( 2654): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=8d6070f7-5ab0-423a-9211-65b6d6659022
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=8d6070f7-5ab0-423a-9211-65b6d6659022, clientIf=7
,D/BluetoothLeScanner( 6131): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 2654): start scan with filters
,D/BtGatt.ScanManager( 2654): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startBlePeerDiscovery: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032996483.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): start: {"pi":"08:EC:A9:50:75:41","pn":"1453032996483.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"1453032996483.6131","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6131): start: OK
,I/jxcore-log( 6131): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 6131): 
,I/io.jxcore.node.ConnectionHelper( 6131): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): shutdown
D/BluetoothSocket( 6131): close() in, this: android.bluetooth.BluetoothSocket@20061d88, channel: 6, state: LISTENING
,D/BluetoothSocket( 6131): close() this: android.bluetooth.BluetoothSocket@20061d88, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@20f3270f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1eca3321mSocket: android.net.LocalSocket@24320346 impl:android.net.LocalSocketImpl@346ee907 fd:FileDescriptor[106]
D/BluetoothSocket( 6131): Closing mSocket: android.net.LocalSocket@24320346 impl:android.net.LocalSocketImpl@346ee907 fd:FileDescriptor[106]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stop: Stopping peer discovery...,
,D/BtGatt.AdvertiseManager( 2654): message : 1
D/BtGatt.GattService( 2654): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
I/TLC_TIMA_PKM_initialize( 1017): initializing...
,I/TLC_TIMA_PKM_initialize( 1017): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1017): process = tima_pkm, process_strlen = 8
D/BtGatt.AdvertiseManager( 2654): stop advertise for client 6
D/BtGatt.AdvertiseManager( 2654):  standardAdvClientIf = 0client.clientIf6,
,D/BtGatt.ScanManager( 2654): allow scan with filters
D/WifiP2pService( 1017): InactiveState{ what=139292 }
,D/BtGatt.ScanManager( 2654): client filter size is = 1available filters are = 13
D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
,I/TZ: qc_tlc_communication( 1017): root = /firmware/image, root_len = 15
D/WifiP2pService( 1017): P2pEnabledState add service
,I/TZ: qc_tlc_communication( 1017): process = tima_pkm, process_strlen = 8
D/WifiP2pService( 1017): add a new client
,I/TZ: qc_tlc_communication( 1017): aligned max_sendmsg_size = 262208 = 0x40040
D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/BtGatt.ScanManager( 2654): set filter index= 10 for clientIf= 7
D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: -1
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/TZ: qc_tlc_communication( 1017): aligned max_recvmsg_size = 262208 = 0x40040
,D/WifiP2pService( 1017): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): onServerStopped
I/TZ: qc_tlc_communication( 1017): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1381): USE_NETWORK : USE_NETWORK OFF
D/BtGatt.GattService( 2654): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2654): Client app is not null!
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2654): stopScan() - queue size =1
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): release: No more listeners, de-initializing...
D/WifiP2pService( 1017): InactiveState{ what=139298 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: No more listeners, de-initializing...
D/WifiP2pService( 1017): P2pEnabledState clear service
D/WifiP2pService( 1017): remove client information from framework
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: NOT_STARTED
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 2654): :scan window =2000 Scan interval = 5000
,D/BtGatt.ScanManager( 2654): filter size is 1
,D/BtGatt.ScanManager( 2654): delete FilterIndex - 10
I/jxcore-log( 6131): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 6131): 
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
I/wpa_supplicant( 1381): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 12
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032996673.6131
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): initialize: My bluetooth address is 08:EC:A9:50:75:41
I/TZ: qc_tlc_communication( 1017): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): stop scan
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue emtpy, scan stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032996673.6131","ra":"08:EC:A9:50:75:41"}
,I/TLC_TIMA_PKM_initialize( 1017): Trustlet response is completed
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6131): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6131): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,D/BluetoothSocket( 6131): bindListen(), new LocalSocket 
D/BluetoothSocket( 6131): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6131): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11f5e05d
,D/BluetoothSocket( 6131): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: OK
I/io.jxcore.node.ConnectionHelper( 6131): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032996673.6131
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): createAdvertiseData: From: 1453032996673.6131 b6a44ad1-d319-4b3a-815d-8b805a47fb51 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): 8:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 8, -20, -87, 80, 117, 65]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6131): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=03ea3b1d-e9e5-41c6-b1bd-e777a1a6440a
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=03ea3b1d-e9e5-41c6-b1bd-e777a1a6440a, clientIf=6
,D/BluetoothLeAdvertiser( 6131): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2654): message : 0
,D/BtGatt.AdvertiseManager( 2654): number of adv instance running0
,D/BtGatt.AdvertiseManager( 2654): size of list is =0
,D/BtGatt.AdvertiseManager( 2654): starting advertising
,D/BtGatt.AdvertiseManager( 2654): isStandardAdvfalse
,D/BtGatt.GattService( 2654): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): starting multi advertising
,D/BtGatt.GattService( 2654): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager( 2654): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=b6a71df2-4c73-48a8-8c5d-df9701c19445
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=b6a71df2-4c73-48a8-8c5d-df9701c19445, clientIf=7
,D/BluetoothLeScanner( 6131): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 2654): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startBlePeerDiscovery: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032996673.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): start: {"pi":"08:EC:A9:50:75:41","pn":"1453032996673.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"1453032996673.6131","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1017): InactiveState{ what=139292 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
D/WifiP2pService( 1017): P2pEnabledState add service
D/WifiP2pService( 1017): add a new client
,D/BtGatt.ScanManager( 2654): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6131): start: OK
,I/jxcore-log( 6131): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 6131): 
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,I/io.jxcore.node.ConnectionHelper( 6131): stop,
D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): stop: Stopping Bluetooth...
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): Shutting down...
D/WifiP2pService( 1017): discovery change broadcast true
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): shutdown
D/BluetoothSocket( 6131): close() in, this: android.bluetooth.BluetoothSocket@35d8351e, channel: 6, state: LISTENING
,D/BluetoothSocket( 6131): close() this: android.bluetooth.BluetoothSocket@35d8351e, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11f5e05d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@71f1ffmSocket: android.net.LocalSocket@1279ebcc impl:android.net.LocalSocketImpl@2f89be15 fd:FileDescriptor[106]
I/wpa_supplicant( 1381): USE_NETWORK : USE_NETWORK OFF
D/BluetoothSocket( 6131): Closing mSocket: android.net.LocalSocket@1279ebcc impl:android.net.LocalSocketImpl@2f89be15 fd:FileDescriptor[106]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: NOT_STARTED,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stop: Stopping peer discovery...
,I/wpa_supplicant( 1381): p2p0: P2P: Reject scan trigger since one is already pending
,D/BtGatt.AdvertiseManager( 2654): message : 1
,D/BtGatt.AdvertiseManager( 2654): stop advertise for client 6
D/BtGatt.AdvertiseManager( 2654):  standardAdvClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: -1
,D/BtGatt.GattService( 2654): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): allow scan with filters
,D/BtGatt.ScanManager( 2654): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager( 2654): set filter index= 11 for clientIf= 7
,D/BtGatt.GattService( 2654): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2654): Client app is not null!
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2654): stopScan() - queue size =1
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
D/BtGatt.GattService( 2654): unregisterClient() - clientIf=7
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 2654): :scan window =2000 Scan interval = 5000
,D/BtGatt.ScanManager( 2654): filter size is 1
D/BtGatt.ScanManager( 2654): delete FilterIndex - 11
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): stop: Stopping services
,D/WifiP2pService( 1017): InactiveState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): stop: Stopping P2P device discovery...
D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
,D/WifiP2pService( 1017): P2pEnabledState clear service
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): release: No more listeners, de-initializing...
,D/WifiP2pService( 1017): remove client information from framework
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: No more listeners, de-initializing...
,I/wpa_supplicant( 1381): P2P-FIND-STOPPED 
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): stop scan
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue emtpy, scan stopped
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: NOT_STARTED
,D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState clear service request
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
I/jxcore-log( 6131): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 6131): 
D/WifiP2pService( 1017): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032996875.6131
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): initialize: My bluetooth address is 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032996875.6131","ra":"08:EC:A9:50:75:41"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6131): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6131): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
D/BluetoothSocket( 6131): bindListen(), new LocalSocket 
,D/BluetoothSocket( 6131): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6131): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22fdaf1b
D/BluetoothSocket( 6131): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: OK
I/io.jxcore.node.ConnectionHelper( 6131): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032996875.6131
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): createAdvertiseData: From: 1453032996875.6131 b6a44ad1-d319-4b3a-815d-8b805a47fb51 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): 8:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 8, -20, -87, 80, 117, 65]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6131): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=4cf5a4ec-0c5e-4387-ac6f-c1c6caba652d
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=4cf5a4ec-0c5e-4387-ac6f-c1c6caba652d, clientIf=6
,D/BluetoothLeAdvertiser( 6131): onClientRegistered() - status=0 clientIf=6
D/BtGatt.AdvertiseManager( 2654): message : 0
,D/BtGatt.AdvertiseManager( 2654): number of adv instance running0
D/BtGatt.AdvertiseManager( 2654): size of list is =0
,D/BtGatt.AdvertiseManager( 2654): starting advertising
,D/BtGatt.AdvertiseManager( 2654): isStandardAdvfalse
,D/BtGatt.GattService( 2654): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): starting multi advertising
,D/BtGatt.GattService( 2654): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager( 2654): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=046e4b09-cd60-41e0-82bd-6a17b5873155
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=046e4b09-cd60-41e0-82bd-6a17b5873155, clientIf=7
,D/BluetoothLeScanner( 6131): onClientRegistered() - status=0 clientIf=7,
,D/BtGatt.GattService( 2654): start scan with filters
,D/BtGatt.ScanManager( 2654): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startBlePeerDiscovery: OK
,D/BtGatt.GattService( 2654): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): allow scan with filters
,D/BtGatt.ScanManager( 2654): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager( 2654): set filter index= 12 for clientIf= 7
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 2654): :scan window =2000 Scan interval = 5000
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032996875.6131","ra":"08:EC:A9:50:75:41"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): start: {"pi":"08:EC:A9:50:75:41","pn":"1453032996875.6131","ra":"08:EC:A9:50:75:41"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"1453032996875.6131","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): start: Starting P2P device discovery...
,D/WifiP2pService( 1017): InactiveState{ what=139292 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 1017): P2pEnabledState add service
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: OK
D/WifiP2pService( 1017): add a new client
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6131): start: OK
,I/jxcore-log( 6131): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 6131): 
,I/io.jxcore.node.ConnectionHelper( 6131): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): shutdown
D/BluetoothSocket( 6131): close() in, this: android.bluetooth.BluetoothSocket@2657e864, channel: 6, state: LISTENING
D/BluetoothSocket( 6131): close() this: android.bluetooth.BluetoothSocket@2657e864, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22fdaf1b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3d949acdmSocket: android.net.LocalSocket@6fe8f82 impl:android.net.LocalSocketImpl@aa8e693 fd:FileDescriptor[106]
D/BluetoothSocket( 6131): Closing mSocket: android.net.LocalSocket@6fe8f82 impl:android.net.LocalSocketImpl@aa8e693 fd:FileDescriptor[106]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stop: Stopping peer discovery...
,D/WifiP2pService( 1017): InactiveState{ what=139265 },
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
,D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1381): USE_NETWORK : USE_NETWORK OFF,
D/BtGatt.AdvertiseManager( 2654): message : 1
D/BtGatt.AdvertiseManager( 2654): stop advertise for client 6
,D/BtGatt.AdvertiseManager( 2654):  standardAdvClientIf = 0client.clientIf6
D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: -1
,I/wpa_supplicant( 1381): p2p0: P2P: Reject scan trigger since one is already pending
D/BtGatt.GattService( 2654): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2654): Client app is not null!
,D/WifiP2pService( 1017): discovery change broadcast true
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2654): stopScan() - queue size =1
,D/BtGatt.ScanManager( 2654): filter size is 1
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=7
,D/BtGatt.ScanManager( 2654): delete FilterIndex - 12
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): release: No more listeners, de-initializing...
,D/WifiP2pService( 1017): InactiveState{ what=139298 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: No more listeners, de-initializing...
D/WifiP2pService( 1017): P2pEnabledState clear service
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: NOT_STARTED
,D/WifiP2pService( 1017): remove client information from framework
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,I/jxcore-log( 6131): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 6131): 
D/BtGatt.ScanManager( 2654): stop scan
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue emtpy, scan stopped
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/wpa_supplicant( 1381): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState clear service request,
D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1017): discovery change broadcast false
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6131): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6131): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6131): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le,.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6131): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6131): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6131): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6131): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6131): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6131): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6131): Service requests cleared successfully
,E/SMD     (  292): DCD OFF
,I/jxcore-log( 6131): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032997794.6131
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): initialize: My bluetooth address is 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032997794.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6131): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6131): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,D/BluetoothSocket( 6131): bindListen(), new LocalSocket 
D/BluetoothSocket( 6131): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6131): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1cdd16c9
D/BluetoothSocket( 6131): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: OK
I/io.jxcore.node.ConnectionHelper( 6131): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032997794.6131
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): createAdvertiseData: From: 1453032997794.6131 b6a44ad1-d319-4b3a-815d-8b805a47fb51 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): 8:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 8, -20, -87, 80, 117, 65]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6131): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Waiting for incoming connections...
,D/BtGatt.GattService( 2654): registerClient() - UUID=73589cae-9b48-4707-8481-181230e0fea4
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=73589cae-9b48-4707-8481-181230e0fea4, clientIf=6
,D/BluetoothLeAdvertiser( 6131): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2654): message : 0,
D/BtGatt.AdvertiseManager( 2654): number of adv instance running0
,D/BtGatt.AdvertiseManager( 2654): size of list is =0
D/BtGatt.AdvertiseManager( 2654): starting advertising
D/BtGatt.AdvertiseManager( 2654): isStandardAdvfalse
,D/BtGatt.GattService( 2654): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): starting multi advertising
,D/BtGatt.GattService( 2654): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager( 2654): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=13d1f73d-1cc3-49f0-893c-3d51c5f76105
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=13d1f73d-1cc3-49f0-893c-3d51c5f76105, clientIf=7
,D/BluetoothLeScanner( 6131): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 2654): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 2654): handling starting scan
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032997794.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): start: {"pi":"08:EC:A9:50:75:41","pn":"1453032997794.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"1453032997794.6131","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1017): InactiveState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: INITIALIZED
,D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): start: Starting P2P device discovery...
D/WifiP2pService( 1017): P2pEnabledState add service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: true
,D/WifiP2pService( 1017): add a new client
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService( 1017): InactiveState{ what=139265 },
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: OK
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: RUNNING_BLE_AND_WIFI
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/io.jxcore.node.ConnectionHelper( 6131): start: OK
D/WifiP2pService( 1017): discovery change broadcast true
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/jxcore-log( 6131): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 6131): 
I/wpa_supplicant( 1381): USE_NETWORK : USE_NETWORK OFF
D/BtGatt.GattService( 2654): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 2654): allow scan with filters
D/BtGatt.ScanManager( 2654): client filter size is = 1available filters are = 13
D/BtGatt.ScanManager( 2654): set filter index= 13 for clientIf= 7
D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 2654): :scan window =2000 Scan interval = 5000
I/jxcore-log( 6131): ok 65 Cannot call startBroadcasting twice
I/jxcore-log( 6131): 
I/io.jxcore.node.ConnectionHelper( 6131): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): shutdown
D/BluetoothSocket( 6131): close() in, this: android.bluetooth.BluetoothSocket@342a8cda, channel: 6, state: LISTENING
D/BluetoothSocket( 6131): close() this: android.bluetooth.BluetoothSocket@342a8cda, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1cdd16c9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@37a4950bmSocket: android.net.LocalSocket@27feffe8 impl:android.net.LocalSocketImpl@efbd601 fd:FileDescriptor[106]
D/BluetoothSocket( 6131): Closing mSocket: android.net.LocalSocket@27feffe8 impl:android.net.LocalSocketImpl@efbd601 fd:FileDescriptor[106]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): onServerStopped
,D/BtGatt.AdvertiseManager( 2654): message : 1
,D/BtGatt.AdvertiseManager( 2654): stop advertise for client 6
D/BtGatt.AdvertiseManager( 2654):  standardAdvClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: -1
,D/BtGatt.GattService( 2654): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2654): Client app is not null!
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2654): stopScan() - queue size =1
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=7,
D/BtGatt.ScanManager( 2654): filter size is 1
D/BtGatt.ScanManager( 2654): delete FilterIndex - 13
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 2654): stop scan
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): stop: Stopping services
,D/WifiP2pService( 1017): InactiveState{ what=139298 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
D/WifiP2pService( 1017): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: NOT_INITIALIZED
D/WifiP2pService( 1017): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService( 1017): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: No more listeners, de-initializing...
,I/wpa_supplicant( 1381): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: NOT_STARTED
I/jxcore-log( 6131): ok 66 Should be able to call stopBroadcasting without error
I/jxcore-log( 6131): 
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState clear service request
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6131): Service requests cleared successfully
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1017): SIOP:: AP = 280
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/wpa_supplicant( 1381): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2654): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2654): Disconnected process message: 10
,I/jxcore-log( 6131): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 6131): 
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE_AND_WIFI,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032999171.6131,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): initialize: My bluetooth address is 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032999171.6131","ra":"08:EC:A9:50:75:41"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): startListeningForIncomingConnections: Starting...
W/BluetoothAdapter( 6131): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothSocket( 6131): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,D/BluetoothSocket( 6131): bindListen(), new LocalSocket 
D/BluetoothSocket( 6131): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6131): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@268576e7
D/BluetoothSocket( 6131): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: OK
I/io.jxcore.node.ConnectionHelper( 6131): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453032999171.6131
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): createAdvertiseData: From: 1453032999171.6131 b6a44ad1-d319-4b3a-815d-8b805a47fb51 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): 8:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 8, -20, -87, 80, 117, 65]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6131): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=bf5fc25b-4513-48d3-beea-8ca2e0fa6b9c
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=bf5fc25b-4513-48d3-beea-8ca2e0fa6b9c, clientIf=6
,D/BluetoothLeAdvertiser( 6131): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2654): message : 0,
D/BtGatt.AdvertiseManager( 2654): number of adv instance running0
D/BtGatt.AdvertiseManager( 2654): size of list is =0
D/BtGatt.AdvertiseManager( 2654): starting advertising
D/BtGatt.AdvertiseManager( 2654): isStandardAdvfalse
,D/BtGatt.GattService( 2654): onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,D/BtGatt.AdvertiseManager( 2654): starting multi advertising
,D/BtGatt.GattService( 2654): onAdvertiseDataSet() - clientIf=6, status=0
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: 0
,D/BtGatt.AdvertiseManager( 2654): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=81009846-0810-49a9-96ab-71e23e725182
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=81009846-0810-49a9-96ab-71e23e725182, clientIf=7
,D/BluetoothLeScanner( 6131): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 2654): start scan with filters
,D/BtGatt.ScanManager( 2654): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startBlePeerDiscovery: OK
,D/BtGatt.GattService( 2654): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 2654): allow scan with filters
D/BtGatt.ScanManager( 2654): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager( 2654): set filter index= 14 for clientIf= 7
D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/BtGatt.ScanManager( 2654): :scan window =2000 Scan interval = 5000
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453032999171.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): start: {"pi":"08:EC:A9:50:75:41","pn":"1453032999171.6131","ra":"08:EC:A9:50:75:41"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"1453032999171.6131","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: INITIALIZED,
D/WifiP2pService( 1017): InactiveState{ what=139292 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): start: Starting P2P device discovery...
D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: true
D/WifiP2pService( 1017): P2pEnabledState add service
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startWifiPeerDiscovery: Wi-Fi Direct OK
D/WifiP2pService( 1017): add a new client
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: OK
D/WifiP2pService( 1017): InactiveState{ what=139265 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: RUNNING_BLE_AND_WIFI
D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
I/io.jxcore.node.ConnectionHelper( 6131): start: OK
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/jxcore-log( 6131): ok 67 Should be able to call startBroadcasting without error
I/jxcore-log( 6131): 
I/io.jxcore.node.ConnectionHelper( 6131): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 6131): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
E/io.jxcore.node.ConnectionHelper( 6131): connect: Invalid Bluetooth address: foobar
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1381): USE_NETWORK : USE_NETWORK OFF
I/jxcore-log( 6131): ok 68 Should not connect to a bad peer
,I/jxcore-log( 6131): 
I/io.jxcore.node.ConnectionHelper( 6131): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): stopListeningForIncomingConnections: Stopping...
D/WifiP2pService( 1017): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): shutdown
D/BluetoothSocket( 6131): close() in, this: android.bluetooth.BluetoothSocket@192fe400, channel: 6, state: LISTENING
,D/BluetoothSocket( 6131): close() this: android.bluetooth.BluetoothSocket@192fe400, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@268576e7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@28dc4439mSocket: android.net.LocalSocket@3fa89a7e impl:android.net.LocalSocketImpl@35505bdf fd:FileDescriptor[106]
D/BluetoothSocket( 6131): Closing mSocket: android.net.LocalSocket@3fa89a7e impl:android.net.LocalSocketImpl@35505bdf fd:FileDescriptor[106]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 2654): message : 1
,D/BtGatt.AdvertiseManager( 2654): stop advertise for client 6
D/BtGatt.AdvertiseManager( 2654):  standardAdvClientIf = 0client.clientIf6
,D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: -1
,D/BtGatt.GattService( 2654): onAdvertiseInstanceDisabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2654): Client app is not null!
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2654): stopScan() - queue size =1
,D/BtGatt.ScanManager( 2654): filter size is 1
D/BtGatt.ScanManager( 2654): delete FilterIndex - 14
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=7
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): stop: Stopping services
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/WifiP2pService( 1017): InactiveState{ what=139298 }
D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): stop scan
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue emtpy, scan stopped
,D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: No more listeners, de-initializing...
,D/WifiP2pService( 1017): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: NOT_STARTED
,I/jxcore-log( 6131): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 6131): 
,D/WifiP2pService( 1017): remove client information from framework
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
I/wpa_supplicant( 1381): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState clear service request
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: true
,I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6131): Service requests cleared successfully
,E/Watchdog( 1017): !@Sync 10,
,I/jxcore-log( 6131): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setDiscoveryMode: Mode set to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453033000494.6131,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): initialize: My bluetooth address is 08:EC:A9:50:75:41,
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453033000494.6131","ra":"08:EC:A9:50:75:41"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6131): getBluetoothService() called with no BluetoothManagerCallback,
,D/BluetoothSocket( 6131): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]},
D/BluetoothSocket( 6131): bindListen(), new LocalSocket 
D/BluetoothSocket( 6131): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6131): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a33eaf5
D/BluetoothSocket( 6131): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): start: OK
I/io.jxcore.node.ConnectionHelper( 6131): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: Peer ID: 08:EC:A9:50:75:41, peer name: 1453033000494.6131
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): bind: Binding a new listener,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): createAdvertiseData: From: 1453033000494.6131 b6a44ad1-d319-4b3a-815d-8b805a47fb51 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6131): 8:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 8, -20, -87, 80, 117, 65]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6131): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BtGatt.GattService( 2654): registerClient() - UUID=be4b2c6d-1d18-42f4-837c-35efe49dcd0b
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=be4b2c6d-1d18-42f4-837c-35efe49dcd0b, clientIf=6
,D/BluetoothLeAdvertiser( 6131): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2654): message : 0
,D/BtGatt.AdvertiseManager( 2654): number of adv instance running0
,D/BtGatt.AdvertiseManager( 2654): size of list is =0
,D/BtGatt.AdvertiseManager( 2654): starting advertising
D/BtGatt.AdvertiseManager( 2654): isStandardAdvfalse
,D/BtGatt.GattService( 2654): onAdvertiseInstanceEnabled() - clientIf=6, status=0,
D/BtGatt.AdvertiseManager( 2654): starting multi advertising
,D/BtGatt.GattService( 2654): onAdvertiseDataSet() - clientIf=6, status=0
D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: 0,
D/BtGatt.AdvertiseManager( 2654): clientIf: 6, Mode: 1, TxPowerLevel: 1, isConnectable: true, Timeout: 0
,D/BtGatt.GattService( 2654): registerClient() - UUID=206d4c24-6eb1-48fa-a5a3-d1851b22a5de
,D/BtGatt.GattService( 2654): onClientRegistered() - UUID=206d4c24-6eb1-48fa-a5a3-d1851b22a5de, clientIf=7
,D/BluetoothLeScanner( 6131): onClientRegistered() - status=0 clientIf=7
,D/BtGatt.GattService( 2654): start scan with filters
,D/BtGatt.ScanManager( 2654): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startBlePeerDiscovery: OK
,D/BtGatt.GattService( 2654): onScanFilterEnableDisabled() - clientIf=7, status=0, action=1
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): allow scan with filters
D/BtGatt.ScanManager( 2654): client filter size is = 1available filters are = 13
,D/BtGatt.ScanManager( 2654): set filter index= 15 for clientIf= 7
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/BtGatt.ScanManager( 2654): :scan window =2000 Scan interval = 5000
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6131): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"1453033000494.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): start: {"pi":"08:EC:A9:50:75:41","pn":"1453033000494.6131","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"1453033000494.6131","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1017): InactiveState{ what=139292 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139292 },
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: INITIALIZED
D/WifiP2pService( 1017): P2pEnabledState add service,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): start: Starting P2P device discovery...
D/WifiP2pService( 1017): add a new client
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 6131): start: OK
D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1381): USE_NETWORK : USE_NETWORK OFF
I/jxcore-log( 6131): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 6131): 
,D/io.jxcore.node.ConnectionHelper( 6131): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
,E/io.jxcore.node.ConnectionHelper( 6131): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/io.jxcore.node.ConnectionHelper( 6131): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/WifiP2pService( 1017): discovery change broadcast true
W/io.jxcore.node.ConnectionHelper( 6131): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
,I/jxcore-log( 6131): ok 71 Disconnect should fail to a non-existant peer 
I/jxcore-log( 6131): 
,I/io.jxcore.node.ConnectionHelper( 6131): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): shutdown
D/BluetoothSocket( 6131): close() in, this: android.bluetooth.BluetoothSocket@21337b56, channel: 6, state: LISTENING
D/BluetoothSocket( 6131): close() this: android.bluetooth.BluetoothSocket@21337b56, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a33eaf5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@d03e7d7mSocket: android.net.LocalSocket@229768c4 impl:android.net.LocalSocketImpl@27fb83ad fd:FileDescriptor[106]
D/BluetoothSocket( 6131): Closing mSocket: android.net.LocalSocket@229768c4 impl:android.net.LocalSocketImpl@27fb83ad fd:FileDescriptor[106]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6131): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6131): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6131): onServerStopped
,D/BtGatt.AdvertiseManager( 2654): message : 1
,D/BtGatt.AdvertiseManager( 2654): stop advertise for client 6
,D/BtGatt.AdvertiseManager( 2654):  standardAdvClientIf = 0client.clientIf6
D/BtGatt.AdvertiseManager( 2654): logClientsSet() - status: -1
,D/BtGatt.GattService( 2654): onAdvertiseInstanceDisabled() - clientIf=6, status=0,
D/BtGatt.GattService( 2654): Client app is not null!
D/BtGatt.GattService( 2654): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2654): stopScan() - queue size =1
,D/BtGatt.GattService( 2654): unregisterClient() - clientIf=7
,D/BtGatt.ScanManager( 2654): filter size is 1
D/BtGatt.ScanManager( 2654): delete FilterIndex - 15
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6131): stop: Stopping services
,D/WifiP2pService( 1017): InactiveState{ what=139298 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6131): release: No more listeners, de-initializing...
,D/BtGatt.GattService( 2654): onScanFilterParamsConfigured() - clientIf=7, status=0, action=1, availableSpace=16
D/WifiP2pService( 1017): P2pEnabledState clear service
D/BtGatt.ScanManager( 2654): callback done for clientIf - 7 status - 0
,D/BtGatt.ScanManager( 2654): stop scan
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2654): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6131): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6131): setState: NOT_STARTED
,D/WifiP2pService( 1017): remove client information from framework
,I/jxcore-log( 6131): ok 72 Should be able to call stopBroadcasting without error
I/jxcore-log( 6131): 
D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/wpa_supplicant( 1381): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState clear service request
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1017): discovery change broadcast false
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6131): onStartSuccess
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6131): onIsAdvertiserStartedChanged: true
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6131): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6131): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6131): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6131): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6131): Service requests cleared successfully
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,I/jxcore-log( 6131): # #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 73 should be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 74 should not be equal
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # setup
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): # teardown
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 75 irrelevant messages should be ignored
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 76 relevant messages should not be ignored
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ok 77 messages from this device should be ignored
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): Tests Complete
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): Toggling radios to false
I/jxcore-log( 6131): 
,D/BluetoothAdapter( 6131): disable()
,D/SettingsProvider( 1017): name = bluetooth_on
,D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1017): mCursor = null
D/WifiService( 1017): setWifiEnabled: false pid=6131, uid=10338
,D/SettingsProvider( 1017): name = wifi_on
,D/BluetoothAdapterState( 2654): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 2654): Setting state to 13
I/BluetoothAdapterState( 2654): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 2654): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2654): updateAdapterState state is 13
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/BluetoothPbapService( 2654): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
D/BluetoothSocket( 2654): close() in, this: android.bluetooth.BluetoothSocket@3ccd29bc, channel: 19, state: LISTENING
D/BluetoothSocket( 2654): close() this: android.bluetooth.BluetoothSocket@3ccd29bc, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f3174d5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@297a3d45mSocket: android.net.LocalSocket@10154c9a impl:android.net.LocalSocketImpl@2f84b9cb fd:FileDescriptor[74]
D/BluetoothSocket( 2654): Closing mSocket: android.net.LocalSocket@10154c9a impl:android.net.LocalSocketImpl@2f84b9cb fd:FileDescriptor[74]
,E/WifiStateMachine( 1017): WifiStateMachine: Leaving Connected state
,I/jxcore-log( 6131): Radios toggled
I/jxcore-log( 6131): 
,I/jxcore-log( 6131): ****TEST TOOK:  ms ****
I/jxcore-log( 6131): 
I/jxcore-log( 6131): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6131): 
,D/btif_config_util( 2654): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
I/chromium( 6131): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 6131): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
D/BluetoothAdapterService( 2654): Autoconnection is available 
D/BluetoothAdapterService( 2654): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 2654): terminating service from this receiver
I/wpa_supplicant( 1381): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1381): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1381): Skip scan - bUseNetwork false
D/BluetoothPbap( 1316): Proxy object disconnected
D/PbapServerProfile( 1316): Bluetooth service disconnected
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterProperties( 2654): onBluetoothDisable()
D/BluetoothAdapterProperties( 2654): mDiscovering is false
,D/SecContentProvider( 1017): uri = 3 selection = isDiscoverableEnabled
W/InputMethodManagerService( 1017): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/BluetoothAdapterState( 2654): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/InputMethodManagerService( 1017): [BT Setting State] State =13
,D/BluetoothTile( 1178):  onBluetoothStateChange:
,D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
E/WifiNative-wlan0( 1017): do suspend true
D/BluetoothTile( 1178): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1178):  getBluetoothState : 13
D/BluetoothTile( 1178):  handleUpdatestate:false name:null
D/BluetoothTile( 1178):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1178): onStateChanged: Bluetooth
I/SamsungIME( 1870): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
V/BluetoothEventManager( 1316): Received android.bluetooth.adapter.action.STATE_CHANGED
D/StatusBarManagerService( 1017): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/StatusBarManagerService( 1017): setIconVisibility slot=bluetooth visible=false
D/BluetoothAdapterProperties( 2654): Scan Mode:20
D/PhoneStatusBar( 1178): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,D/BluetoothAdapterState( 2654): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 2654): btif_dm_generic_evtnup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 2654): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
E/bt-btif ( 2654): cmd socket is not created
,E/BtOppRfcommListener( 2654): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/btif_config_util( 2654): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/BluetoothSocket( 2654): close() in, this: android.bluetooth.BluetoothSocket@118668c1, channel: 5, state: LISTENING
D/BluetoothSocket( 2654): close() this: android.bluetooth.BluetoothSocket@118668c1, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a9eba24, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@306b9866mSocket: android.net.LocalSocket@2b2327a7 impl:android.net.LocalSocketImpl@2636f454 fd:FileDescriptor[76]
D/BluetoothSocket( 2654): Closing mSocket: android.net.LocalSocket@2b2327a7 impl:android.net.LocalSocketImpl@2636f454 fd:FileDescriptor[76]
I/BtOppRfcommListener( 2654): stopping Accept Thread
D/BluetoothSocket( 2654): close() in, this: android.bluetooth.BluetoothSocket@10cfcffd, channel: 12, state: LISTENING
D/BluetoothSocket( 2654): close() this: android.bluetooth.BluetoothSocket@10cfcffd, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ab4658e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1488d4f2mSocket: android.net.LocalSocket@14509743 impl:android.net.LocalSocketImpl@353901c0 fd:FileDescriptor[79]
D/BluetoothSocket( 2654): Closing mSocket: android.net.LocalSocket@14509743 impl:android.net.LocalSocketImpl@353901c0 fd:FileDescriptor[79]
I/BtOppRfcommListener( 2654): BluetoothSocket listen thread finished
,E/bt-btm  ( 2654): btm_ble_start_auto_conn start : 0, 0
W/bt-btif ( 2654): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/CommandListener(  279): Clearing all IP addresses on wlan0
W/ContextImpl( 1316): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/bt-l2cap( 2654): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2654): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2654): L2CAP - PSM: 0x001b not found for deregistration
V/NativeCrypto( 1719): Read error: ssl=0xb752aed0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1719): SSL shutdown failed: ssl=0xb752aed0: I/O error during system call, Broken pipe
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 2
E/ConnectivityService( 1017): updateNetworkInfo()
I/jxcore-log( 6131): Toggling radios to false
I/jxcore-log( 6131): 
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/WifiP2pService( 1017): InactiveState{ what=131204 }
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/BluetoothAdapter( 6131): disable()
D/WifiNetworkAgent( 1017): NetworkAgent: NetworkAgent channel lost
V/BluetoothOppManager( 2654): cleanUp...
D/WifiP2pService( 1017): P2pEnabledState{ what=131204 }
,D/ConnectivityService( 1017): reportBadNetwork(NetworkAgentInfo [WIFI () - 503]) by 10011
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling,
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,D/WifiP2pService( 1017): sending p2p connection changed broadcast: FAILED
,I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1017): Tagging socket 345 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
I/qtaguid ( 1017): Untagging socket 345
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/ConnectivityService( 1017): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/ConnectivityService( 1017): notifyType LOST for NetworkAgentInfo [WIFI () - 503]
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiScanningService( 1017): SCAN_AVAILABLE : 1
D/ConnectivityService( 1017): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiScanningService( 1017): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/CSLegacyTypeTracker( 1017): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/CSLegacyTypeTracker( 1017): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=false
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/RttService( 1017): SCAN_AVAILABLE : 1
D/RttService( 1017): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/TelephonyNetworkFactory( 1457): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1457): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524292
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityService( 1017): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): doQuit - quitNow()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1017): updateNetworkInfo()
,E/BluetoothManagerService( 1017): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
D/WifiService( 1017): setWifiEnabled: false pid=6131, uid=10338
D/SecContentProvider2( 1017): mCursor = null
D/SettingsProvider( 1017): name = wifi_on
,I/jxcore-log( 6131): Radios toggled
I/jxcore-log( 6131): 
,D/WifiDisplayController( 1017): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1017): onP2pDisconnected
,D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,E/WifiController( 1017): illegal state found both WifiController and WifiStateMachine
,D/Tethering( 1017): MasterInitialState.processMessage what=3
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): updateIfacesLocked()
V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/StatusBar.NetworkController( 1178): EthernetConnected: false
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1178): updateDataNetType()
D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1178): updateLTEICONDataNetType:0
,V/NetworkStats( 1017): performPollLocked() took 7ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/DockEventReceiver( 1316): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1316): onReceive
,D/IpRemoteDisplayController( 1017): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1017): WfdBridgeServer is already null
,D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
,D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/BluetoothStatusReceiver( 1178): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1178): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6700): MountEmulatedStorage(),
E/Zygote  ( 6700): v2
I/libpersona( 6700): KNOX_SDCARD checking this for 10055
I/libpersona( 6700): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6700 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 6700): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,E/ConnectivityService( 1017): updateNetworkInfo()
D/WifiP2pService( 1017): sending p2p connection changed broadcast: DISCONNECTED
,E/WifiStateMachine( 1017): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
,D/WifiDisplayController( 1017): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false,
I/SELinux ( 6700): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/WifiDisplayController( 1017): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayController( 1017): disconnect
D/WifiDisplayController( 1017): updateConnection
D/WifiDisplayController( 1017): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/SELinux ( 6700): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/AllShareCastTile( 1178): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
E/WifiNative-wlan0( 1017): do suspend true
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1178): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
D/WifiP2pService( 1017): P2pDisablingState
D/WifiP2pService( 1017): P2pDisablingState{ what=147458 }
D/WifiP2pService( 1017): p2p socket connection lost
D/WifiDisplayController( 1017): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1017): onP2pDisconnected
D/IpRemoteDisplayController( 1017): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1017): WfdBridgeServer is already null
D/WifiP2pService( 1017): P2pDisabledState
D/WifiP2pService( 1017): P2pDisabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
,D/WifiP2pService( 1017): P2pDisabledState{ what=143375 }
,D/WifiP2pService( 1017): DefaultState{ what=143375 }
,D/CommandListener(  279): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/TimaKeyStoreProvider( 6700): TimaSignature is unavailable
,D/ActivityThread( 6700): Added TimaKeyStore provider,
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
I/wpa_supplicant( 1381): p2p0: State: DISCONNECTED -> DISCONNECTED
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/bt-l2cap( 2654): btif_in_execute_service_request : 25 disabled
,W/bt-l2cap( 2654): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 2654): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2654): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2654): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2654): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2654): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2654): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2654): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 2654): ag scb idx 1 not allocated
W/bt-btif ( 2654): ag scb idx 2 not allocated
E/bt-btif ( 2654): BTA AG is already disabled, ignoring ...
I/bt_userial_mct( 2654): exiting userial_read_thread,
D/bt_userial_mct( 2654): Leaving userial_evt_read_thread()
D/bt_userial_mct( 2654): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 2654): hw_epilog_process
D/bt_userial_mct( 2654): userial_close
I/bt_vendor( 2654): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=false enabledDesc:null,
D/HotspotTile( 1178): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/HotspotTile( 1178): onReceive : 0, 0
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-QSTileView( 1178): onStateChanged: Wi-Fi
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/STATUSBAR-WifiQuickSettingButton( 1178): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1178): Wifi onReceive(0)
D/WifiCredService( 1316): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/AndroidRuntime( 6690): 
D/AndroidRuntime( 6690): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6690): CheckJNI is OFF,
D/AndroidRuntime( 6690): readGMSProperty: start,
D/AndroidRuntime( 6690): readGMSProperty: already setted!!
D/AndroidRuntime( 6690): propertySet: couldn't set property (it is from app),
D/AndroidRuntime( 6690): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6690): readGMSProperty: end
D/AndroidRuntime( 6690): addProductProperty: start
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/UserAnalysis.PlaceProvider( 6700): PlaceProvider onCreate()
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3,
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3,
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3,
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3,
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3,
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/UserAnalysis.SecureDbManager( 6700): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 6700): SecurePlaceDbHelper() 
D/UserAnalysis( 6700): Create SecureDbHelper
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3,
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/IntelligenceServiceApplication( 6700): onCreate()
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,I/ActivityManager( 1017): Killing 5874:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,D/IntelligenceServiceApplication( 6700): no applications having user consent for prediction
,V/PlaceDetection v1.0.19 ( 6700): [PlaceDetection::stopService] Service stopped.
,D/AuthorizationBluetoothService( 1719): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/PlaceDetection v1.0.19 ( 6700): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 1686): Starting #14
I/Hs20UtilService( 1686): Message received 5007,
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/wpa_supplicant( 1381): Blacklist: Clear (all) 
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6739): MountEmulatedStorage(),
E/Zygote  ( 6739): v2
I/libpersona( 6739): KNOX_SDCARD checking this for 10064
I/libpersona( 6739): KNOX_SDCARD not a persona
I/SELinux ( 6739): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6739 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6739): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6739): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6739): TimaSignature is unavailable
,D/ActivityThread( 6739): Added TimaKeyStore provider
,I/wpa_supplicant( 1381): p2p0: CTRL-EVENT-TERMINATING 
I/Nat464Xlat( 1017): interfaceLinkStateChanged p2p0, false
D/Tethering( 1017): interfaceLinkStateChanged p2p0, false
W/ResourcesManager( 6739): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/Tethering( 1017): interfaceStatusChanged p2p0, false
,D/FileShare-Client( 6739): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,E/AffinityControl( 6690): AffinityControl: registerfunction enter
W/libprocessgroup( 1017): failed to open /acct/uid_10152/pid_5874/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1381): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,D/FileShare-Client( 6739): ClientBroadcastReceiver.onReceive - disconnected
I/wpa_supplicant( 1381): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1381): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1381): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1381): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,D/Tethering( 1017): InitialState.processMessage what=4
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
E/Tethering( 1017): No numeric data
D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1017): clearTetheredNotification()
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/HotspotTile( 1178): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1178): updateTetherState():false, false
V/NetworkStats( 1017): performPollLocked() took 4ms
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/FileShare-Client( 6739): Outbound.stopDelayTimer - 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/AndroidRuntime( 6690): Calling main entry com.android.commands.pm.Pm
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
,D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1017): START PACKAGE DELETE: observer{337010214}
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1017): !@killApplicatoin: 10338, uninstall pkg
,E/Zygote  ( 6756): MountEmulatedStorage()
,E/Zygote  ( 6756): v2,
,I/libpersona( 6756): KNOX_SDCARD checking this for 10065
I/libpersona( 6756): KNOX_SDCARD not a persona
,I/SELinux ( 6756): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6756 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5858:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,I/SELinux ( 6756): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6756): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
,I/ActivityManager( 1017): Killing 6131:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
,I/bt_vendor( 2654): bt-vendor : BT_VND_OP_POWER_CTRL: Off,
I/bt_vendor( 2654): bluetooth satus is on
I/bt_vendor( 2654): bt-vendor : resetting BT status
I/bt_vendor( 2654): Starting hciattach daemon
,I/bt_vendor( 2654): try to set false
I/bt_vendor( 2654): Starting hciattach daemon
I/bt_vendor( 2654): try to set false
I/bt_vendor( 2654): cleanup
I/GKI_LINUX( 2654): gki_task task_id=0 [BTU] terminating
D/TimaKeyStoreProvider( 6756): TimaSignature is unavailable
D/ActivityThread( 6756): Added TimaKeyStore provider
I/GKI_LINUX( 2654): GKI_exit_task 0 done,
I/GKI_LINUX( 2654): GKI_shutdown(): task [BTU] terminated
,I/PowerManagerService( 1017): [PWL] Off : 225s ago
I/PowerManagerService( 1017): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1017): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1017, ws=null) (elapsedTime=474)
,W/PackageSettings( 1017): Skipping PackageSetting{19ca7f4 com.example.hello/10346} due to missing metadata
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{4cd9922 u0 com.test.thalitest/.MainActivity t20}
,E/JavaBinder( 1017): !!! FAILED BINDER TRANSACTION !!!
,D/InputDispatcher( 1017): Focus left window: 6131
,I/SurfaceFlinger(  258): id=14 Removed NainActivit (6/8)
,I/SurfaceFlinger(  258): id=14 Removed NainActivit (-2/8)
,D/InputDispatcher( 1017): Focused application released
E/JavaBinder( 1017): !!! FAILED BINDER TRANSACTION !!!
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/BluetoothAdapterState( 2654): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 2654): isSecureModeOn:false
D/BluetoothAdapterService( 2654): mProfilesStarted : true supportedProfileServices.length : 12
,W/BluetoothAdapterService( 2654): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2654): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2654): Not skipping com.android.bluetooth.gatt.GattService
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,I/wpa_supplicant( 1381): Blacklist: Clear (all) 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2654): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2654): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 2654): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.DebugUtils( 2654): handleDebugAction() action=null
,D/BtGatt.GattService( 2654): Received stop request...Stopping profile...
,D/BtGatt.GattService( 2654): stop()
,D/BtGatt.AdvertiseManager( 2654): advertise clients cleared
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5858/cgroup.procs: No such file or directory
D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/art     ( 4062): Explicit concurrent mark sweep GC freed 3116(187KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 782us total 35.370ms
,I/wpa_supplicant( 1381): wlan0: CTRL-EVENT-TERMINATING ,
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): interfaceStatusChanged wlan0, false
,I/art     ( 6003): Explicit concurrent mark sweep GC freed 95(15KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 7.255ms total 51.278ms
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1795): Ignoring removeGeofence because network location is disabled.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/SamsungIME( 1870): mOCRHelper is null
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,E/WifiStateMachine( 1017): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [21]
D/BluetoothAdapterService( 2654): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35d30385
,W/BluetoothAdapterService( 2654): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2654): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/ResourcesManager( 1457): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/BluetoothAdapterService( 2654): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/FileShare-Server( 6756): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,W/Settings( 6187): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1178): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1178): Wifi onReceive(1)
,D/STATUSBAR-QSTileView( 1178): onStateChanged: Wi-Fi,
,D/HotspotTile( 1178): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/WifiCredService( 1316): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1017): no available spell checker services found
,W/Settings( 1795): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HotspotTile( 1178): onReceive : 1, 0
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/BluetoothAdapterService( 2654): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2654): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 2654): Not skipping com.android.bluetooth.hid.HidService
,D/HeadsetService( 2654): Received stop request...Stopping profile...
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2654): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2654): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 2654): Not skipping com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 2654): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35d30385
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1017): Killing 5894:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #31
,D/HeadsetProfile( 1316): Bluetooth service disconnected
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2654): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 2654): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 2654): Not skipping com.android.bluetooth.pan.PanService
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2654): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2654): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 2654): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2654): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 2654): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 2654): Not skipping com.broadcom.bt.service.sap.SapService
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,W/BluetoothAdapterService( 2654): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,D/BtSettings.ProfileConfig( 2654): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 2654): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 2654): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2654): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 2654): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 2654): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2654): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 2654): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2654): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2654): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 2654): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,D/BluetoothAdapterState( 2654): Stopping profile services that were post enabled
E/BluetoothAdapterService(903021445)( 2654): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 71690(4MB) AllocSpace objects, 68(1141KB) LOS objects, 33% free, 24MB/36MB, paused 3.120ms total 220.048ms
,I/art     ( 1017): WaitForGcToComplete blocked for 99.349ms for cause Explicit
,D/A2dpService( 2654): Received stop request...Stopping profile...
,D/A2dpStateMachine( 2654): Exit Disconnected: -1
,D/BluetoothAdapterService( 2654): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35d30385
,D/HidService( 2654): Received stop request...Stopping profile...
,D/HidService( 2654): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 2654): Cleaning up Bluetooth HID Interface...
,W/bt-btif ( 2654): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2654): Cleaning up Bluetooth GID callback object
,D/BluetoothA2dp( 1316): Proxy object disconnected
D/A2dpProfile( 1316): Bluetooth service disconnected
,D/BluetoothAdapterService( 2654): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35d30385
,E/BluetoothAdapterService(903021445)( 2654): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2654): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2654): Profile still running: com.android.bluetooth.hid.HidService
,D/BluetoothInputDevice( 1316): Proxy object disconnected
D/HidProfile( 1316): Bluetooth service disconnected
,W/BluetoothHeadsetServiceJni( 2654): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2654): Cleaning up Bluetooth Handsfree callback object
,D/HealthService( 2654): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2654): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35d30385
,D/PanService( 2654): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2654): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35d30385
,D/BluetoothPan( 1316): BluetoothPAN Proxy object disconnected
D/PanProfile( 1316): Bluetooth service disconnected
,D/BluetoothMapService( 2654): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2654): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35d30385
,D/BluetoothMap( 1316): Proxy object disconnected
D/MapProfile( 1316): Bluetooth service disconnected
,D/SapService( 2654): Received stop request...Stopping profile...
D/SapService( 2654): Stopping Bluetooth SapService
D/BluetoothAdapterService( 2654): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35d30385
,E/BluetoothAdapterService(903021445)( 2654): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2654): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2654): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 2654): Proxy object disconnected
D/BluetoothAdapterService( 2654): Bluetooth A2dp source service disconnected
,I/GKI_LINUX( 2654): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2654): GKI_exit_task 2 done
I/GKI_LINUX( 2654): GKI_shutdown(): task [A2DP-MEDIA] terminated
,E/BluetoothAdapterService(903021445)( 2654): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2654): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2654): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/Bluetoothsap( 1316): BluetoothSAP Proxy object disconnected
D/SapProfile( 1316): Bluetooth service disconnected
E/BluetoothAdapterService(903021445)( 2654): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2654): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2654): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 2654): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2654): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(903021445)( 2654): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2654): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2654): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 2654): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2654): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(903021445)( 2654): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2654): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2654): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(903021445)( 2654): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
W/BluetoothSAPServiceJni( 2654): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2654): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,D/BluetoothAdapterState( 2654): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2654): Setting state to 10
I/BluetoothAdapterState( 2654): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2654): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2654): updateAdapterState state is 10
,D/BluetoothAdapter( 1457): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1457): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapterService( 2654): Autoconnection is available 
D/BluetoothAdapterService( 2654): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 2654): Entering OffState
,D/BluetoothAdapter( 2654): onBluetoothStateChange: up=false
D/BluetoothAdapter( 2654): Bluetooth is turned off, stop adv and scan
,D/BluetoothPbap( 1316): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1440): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1440): Bluetooth is turned off, stop adv and scan
,D/BluetoothA2dp( 1316): onBluetoothStateChange: up=false
,D/RegisteredServicesCache( 1440): empty dynamic service
,D/BluetoothAdapter( 1795): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1795): Bluetooth is turned off, stop adv and scan
,D/BluetoothMap( 1316): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1017): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1017): Bluetooth is turned off, stop adv and scan
,D/BluetoothInputDevice( 1316): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1429): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1429): Bluetooth is turned off, stop adv and scan
,D/BluetoothA2dp( 2654): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1316): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1316): Bluetooth is turned off, stop adv and scan
,D/BluetoothA2dp( 1017): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1178): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1178): Bluetooth is turned off, stop adv and scan
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/Bluetoothsap( 1316): onBluetoothStateChange: up=false
,D/Bluetoothsap( 1316): Unbinding service...
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BluetoothManagerService( 1017): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService( 1017): Broadcasting onBluetoothServiceUp() to 0 receivers.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BluetoothAdapter( 1178): 163080860: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
D/BluetoothAdapter( 1178): 163080860: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 1178): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothTile( 1178):  getBluetoothState : 10
,D/BluetoothAdapter( 1178): 163080860: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1178): 163080860: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1178): 163080860: getState() :  mService = null. Returning STATE_OFF
D/StatusBarManagerService( 1017): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/StatusBarManagerService( 1017): setIconVisibility slot=bluetooth visible=false
D/PhoneStatusBar( 1178): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,V/BluetoothEventManager( 1316): Received android.bluetooth.adapter.action.STATE_CHANGED
,I/SamsungIME( 1870): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/GKI_LINUX( 2654): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2654): GKI_exit_task 1 done
,I/GKI_LINUX( 2654): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2654): cleanupNative: return from cleanup
,D/RCPManagerService( 1017): PackageReceiver onReceive()
,I/art     ( 2654): System.exit called, status: 0
,I/AndroidRuntime( 2654): VM exiting with result code 0, cleanup skipped.
,I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1017): clearDefaults: com.test.thalitest
,I/CrashAnrDetector( 1017): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5894/cgroup.procs: No such file or directory
,I/ActivityManager( 1017): Process com.android.bluetooth (pid 2654)(adj 0) has died(109,651)
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 12699(631KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 5.364ms total 187.927ms
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10338
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=20_task.xml
,D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED,
V/EnterpriseBillingPolicy( 1017): uID is 10338
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter,
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ApplicationPolicy( 1017): updateDataUsageMap
,D/PackageManager( 1017): delete codoeFile: 
,D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
,I/AASA_removePackage( 1017): UID=10338 Target=com.test.thalitest
,D/PackageManager( 1017): result of delete: 1{337010214}
,D/AndroidRuntime( 6690): Shutting down VM
,E/SMD     (  292): DCD OFF
,D/Tethering( 1017): interfaceRemoved wlan0
,E/Tethering( 1017): attempting to remove unknown iface (wlan0), ignoring
,W/art     ( 6690): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/InputMethodManagerService( 1017): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1017): [BT Setting State] State =10
I/InputMethodManagerService( 1017): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/Tethering( 1017): interfaceRemoved p2p0,
E/Tethering( 1017): attempting to remove unknown iface (p2p0), ignoring
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1686): Starting #15
I/Hs20UtilService( 1686): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1686): Starting #16
D/SecurityLogAgent( 6386): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6386): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6386): StateMachine : Current State = 1
D/SecurityLogAgent( 6386): StateMachine : Changed Current State = 1
,I/Hs20UtilService( 1686): Message received 5011
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/PCWCLIENTTRACE_PushUtil( 5758): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5758): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5758): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5758): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1017): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
,I/splitIntent( 1017): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
,I/splitIntent( 1017): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
,I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
I/PCWCLIENTTRACE_SYSTEMReceiver( 5758): noConnectivity : true
,V/MusicLeanback( 6231): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/DIAGMON_AGENT( 6285): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6285): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6285): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6285): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything

```
