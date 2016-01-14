#### Test 55613145c131883_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
I/PowerManagerService( 1022): [PWL] Off : 75s ago
,--------- beginning of main
D/AndroidRuntime( 6066): 
D/AndroidRuntime( 6066): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6066): CheckJNI is OFF
D/AndroidRuntime( 6066): readGMSProperty: start
D/AndroidRuntime( 6066): readGMSProperty: already setted!!
D/AndroidRuntime( 6066): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6066): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6066): readGMSProperty: end
D/AndroidRuntime( 6066): addProductProperty: start
E/AffinityControl( 6066): AffinityControl: registerfunction enter
D/AndroidRuntime( 6066): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1022): inState():  stateMachine is null !!
I/PersonaManagerService( 1022): PersonaId don't exist
I/ActivityManager( 1022): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1022): mDVFSHelper.acquire()
D/FocusedStackFrame( 1022): Set to : 0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1022): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1022): *FMB* installDecor flags : 25362712
E/Zygote  ( 6078): MountEmulatedStorage()
E/Zygote  ( 6078): v2
I/libpersona( 6078): KNOX_SDCARD checking this for 10338
I/libpersona( 6078): KNOX_SDCARD not a persona
I/ActivityManager( 1022): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6078 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1022): Focused application set to: xxxx
I/SELinux ( 6078): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/InputDispatcher( 1022): Focus left window: 1480
D/AndroidRuntime( 6066): Shutting down VM
I/SELinux ( 6078): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6078): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, uhalitest
D/TimaKeyStoreProvider( 6078): TimaSignature is unavailable
D/ActivityThread( 6078): Added TimaKeyStore provider
D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
V/WindowManager( 1022): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1022): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1022):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1480): updateVisibility : ActivityRecord{1e5d73c8 token=android.os.BinderProxy@2d80faa7 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1480): onTrimMemory. Level: 20
I/WebViewFactory( 6078): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6078): Time to load native libraries: 1 ms (timestamps 4068-4069)
I/LibraryLoader( 6078): Expected native library version number "",actual native library version number ""
W/art     ( 6066): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6078): Binding Chromium to main looper Looper (main, tid 1) {1d55844e}
,I/LibraryLoader( 6078): Expected native library version number "",actual native library version number ""
,I/chromium( 6078): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6078): Initializing chromium process, singleProcess=true
,W/art     ( 6078): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6078): ApplicationContext is null in ApplicationStatus
,W/chromium( 6078): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6078): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6078): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6078): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6078): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6078): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6078): Local Branch: 
I/Adreno-EGL( 6078): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6078): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6078):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,E/SMD     (  289): DCD OFF
,W/art     ( 6078): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6078): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6078): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6078): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6078): CordovaWebView is running on device made by: samsung
,W/art     ( 6078): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6078): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1022): Activity pause timeout for ActivityRecord{28a84342 u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 6078): Render dirty regions requested: true
,D/ActivityManager( 1022): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1022): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1022): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1022): handleActiveUserChange for user 0
,D/PersonaManagerService( 1022): getPersonasForUser(): returning null!
,W/chromium( 6078): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6078): updateVisibility : ActivityRecord{3d026f7b token=android.os.BinderProxy@2a08af75 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6078): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 6078): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1022): Focus entered window: 6078
,D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 6078): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6078): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6078): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6078): Enabling debug mode 0
,D/InputMethodManagerService( 1022): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1022): Displayed Component not be shown by security: +626ms (total +38s77ms)
,W/ActivityManager( 1022): mDVFSHelper.release()
I/Timeline( 1022): Timeline: Activity_windows_visible id: ActivityRecord{28a84342 u0 com.test.thalitest/.MainActivity t20} time:154546
,W/IInputConnectionWrapper( 6078): showStatusIcon on inactive InputConnection
,I/Timeline( 6078): Timeline: Activity_idle id: android.os.BinderProxy@2a08af75 time:154551
,I/SurfaceFlinger(  258): id=12 Removed uhalitest (7/9)
,I/SurfaceFlinger(  258): id=12 Removed uhalitest (-2/9)
,I/SamsungIME( 1770): getCurrentCandidateView
,D/SamsungIME( 1770): Dismiss ExpandCandiate
,I/SamsungIME( 1770): getDebugLevel  : 0x4f4c
,W/BindingManager( 6078): Cannot call determinedVisibility() - never saw a connection for the pid: 6078
,I/SamsungIME( 1770): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1770): KeybaordView init() : load resources
,I/SamsungIME( 1770): getCurrentKeyboard
I/SamsungIME( 1770): getTextKeyboard
,D/SamsungIME( 1770): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 6078): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6078): JniHelper::setJavaVM(0xb70ca448), pthread_self() = -1218304016
,D/JX-Cordova( 6078): jxcore cordova android initializing
,V/AlarmManager( 1022): waitForAlarm result :4
,I/BooksSync( 6001): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6001): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6001): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6001): Soft error
E/BooksSync( 6001): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6001): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6001): Sync error
E/BooksSync( 6001): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6001): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6001): Finished books sync
,D/SyncManager( 1022): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 155517, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1022): mCursor = null
,W/jxcore-log( 6078): Initializing JXcore engine
W/jxcore-log( 6078): JXcore engine is ready
,W/jxcore-log( 6078): Starting JXcore engine
,E/audit   ( 1822): type=1400 msg=audit(1452773895.828:205): avc:  denied  { ioctl } for  pid=6078 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1822):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1822): type=1300 msg=audit(1452773895.828:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=befc8d58 items=0 ppid=311 ppcomm=main pid=6078 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1822): type=1320 msg=audit(1452773895.828:205): 
,W/jxcore-log( 6078): Platform android
W/jxcore-log( 6078): 
W/jxcore-log( 6078): Process ARCH arm
W/jxcore-log( 6078): 
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2658): Disconnected process message: 10
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
I/jxcore-log( 6078): JXcore Cordova bridge is ready!
I/jxcore-log( 6078): 
W/jxcore-log( 6078): JXcore engine is started
I/Choreographer( 6078): Skipped 122 frames!  The application may be doing too much work on its main thread.
I/chromium( 6078): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 6078): Toggling radios to true
I/jxcore-log( 6078): 
D/BluetoothAdapter( 6078): enable()
D/BluetoothAdapter( 6078): enable(): BT is already enabled..!
D/SecContentProvider( 1022): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1022): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1022): mCursor = null
D/WifiService( 1022): setWifiEnabled: true pid=6078, uid=10338
W/ActivityManager( 1022): Permission Denial: getCurrentUser() from pid=6078, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1022): Failed getting userId using ActivityManagerNative
W/WifiService( 1022): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6078, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1022): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1022): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1022): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1022): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1022): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1022): name = wifi_on
I/WifiService( 1022): disconnect: pid=6078, uid=10338
I/wpa_supplicant( 1401): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
E/SMD     (  289): DCD OFF
I/jxcore-log( 6078): Radios toggled
I/jxcore-log( 6078): 
I/jxcore-log( 6078): My device name is: samsung-SM-A300FU
I/jxcore-log( 6078): 
I/wpa_supplicant( 1401): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1401): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1401): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1401): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1401): wlan0: State: DISCONNECTED -> DISCONNECTED
I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, false
D/Tethering( 1022): interfaceLinkStateChanged wlan0, false
D/Tethering( 1022): interfaceStatusChanged wlan0, false
D/Tethering( 1022): InitialState.processMessage what=4
E/wpa_supplicant( 1401): Cmd 35605 not handled
E/WifiStateMachine( 1022): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1401): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1401): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1401): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1401): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1401): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1401): First Scan Start
I/wpa_supplicant( 1401): Scan requested (ret=0) - scan timeout 30 seconds
I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, false
D/Tethering( 1022): interfaceLinkStateChanged wlan0, false
D/Tethering( 1022): interfaceStatusChanged wlan0, false
E/Tethering( 1022): No numeric data
D/Tethering( 1022): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1022): clearTetheredNotification()
E/WifiConfigStore( 1022): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, false
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
V/NetworkStats( 1022): performPollLocked(flags=0x1)
D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false
D/NetworkStatsFactory( 1022): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1022): UpdateStatsForKnox main else ---
D/Tethering( 1022): interfaceLinkStateChanged wlan0, false
D/Tethering( 1022): interfaceStatusChanged wlan0, false
V/NetworkStats( 1022): performPollLocked() took 6ms
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
E/WifiNative-wlan0( 1022): do suspend true
D/WifiP2pService( 1022): InactiveState{ what=143375 }
D/WifiP2pService( 1022): P2pEnabledState{ what=143375 }
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/CommandListener(  279): Clearing all IP addresses on wlan0
E/WifiStateMachine( 1022): Start Disconnecting Watchdog 1
D/ConnectivityService( 1022): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/wpa_supplicant( 1401): wlan0: Setting scan request: 0 sec 0 usec
D/ConnectivityService( 1022): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
E/ConnectivityService( 1022): updateNetworkInfo()
E/ConnectivityService( 1022): updateNetworkInfo()
I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb75cb7c8
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1218661064)
I/WifiTrafficPoller( 1022): evaluateTrafficStatsPolling
E/WifiNative-wlan0( 1022): do suspend true
D/WifiP2pService( 1022): InactiveState{ what=143375 }
D/WifiP2pService( 1022): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/NativeCrypto( 1715): Read error: ssl=0xb7630690: I/O error during system call, Connection timed out
,V/NativeCrypto( 1715): SSL shutdown failed: ssl=0xb7630690: I/O error during system call, Broken pipe,
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1022): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
W/ActivityManager( 1022): userId = 0, bbcId = -10000
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): ValidatedState{ when=-3ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): DefaultState{ when=-3ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/System.out( 1022): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1022): Tagging socket 351 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1022, getuid(): 1000
,I/qtaguid ( 1022): Untagging socket 351
I/System.out( 1022): (HTTPLog)-Static: isSBSettingEnabled false
,I/Hs20UtilService( 2104): Starting #8
I/Hs20UtilService( 2104): Message received 5007
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1321): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1321): MountReceiver.mPrefHandler - 7002
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1218661064) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb75cb7c8
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1022): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6135 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/Zygote  ( 6135): MountEmulatedStorage()
,E/Zygote  ( 6135): v2
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener(  279): Clearing all IP addresses on wlan0
I/libpersona( 6135): KNOX_SDCARD checking this for 10102
I/libpersona( 6135): KNOX_SDCARD not a persona,
D/WIFI_P2P( 1022): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1022): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524292
D/ConnectivityService( 1022): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/TelephonyNetworkFactory( 1451): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/ConnectivityService( 1022): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1451): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 1022): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1022): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1022): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/EntConnectivity( 1022): Not allowed due to - mEnabled false - primarySimSlot false
,I/SELinux ( 6135): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/ConnectivityService( 1022): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): doQuit - quitNow()
,D/EntConnectivity( 1022): Not allowed due to - mEnabled false - primarySimSlot false
D/Tethering( 1022): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
I/SELinux ( 6135): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/Tethering( 1022): MasterInitialState.processMessage what=3
,E/SELinux ( 6135): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
V/NetworkStats( 1022): updateIfacesLocked()
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
V/NetworkStats( 1022): performPollLocked(flags=0x1),
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Validated
D/NetworkStatsFactory( 1022): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1022): UpdateStatsForKnox main else ---
D/WifiNetworkAgent( 1022): NetworkAgent: NetworkAgent channel lost
D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
I/WifiTrafficPoller( 1022): evaluateTrafficStatsPolling
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
V/NetworkStats( 1022): performPollLocked() took 9ms
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
V/NetworkStats( 1022): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/WIFI    ( 1022): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/SecContentProvider2( 1022): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1022): mCursor = null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/SecContentProvider2( 1022): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1022): mCursor = null
,D/TimaKeyStoreProvider( 6135): TimaSignature is unavailable
,D/ActivityThread( 6135): Added TimaKeyStore provider
,W/ResourcesManager( 6135): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,D/PhoneApp( 1451): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,D/FileWriteThread_Telephony( 1451): FileWriteThread : threadType = 3
,I/Babel_SMS( 6135): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6135): MmsConfig.loadMmsSettings
I/Babel_SMS( 6135): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel_SMS( 6135): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6135): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6135): MmsConfig.loadFromResources
,E/Babel_SMS( 6135): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6135): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  284): getCameraInfo: X
,W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  284): getCameraInfo: X
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6135): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6135): startup - clean
,I/Babel   ( 6135): deleted: false for 0
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2104): Starting #9
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/Hs20UtilService( 2104): Message received 5007
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1321): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1321): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6135): Unrecognized profile 2130706433 for video/avc
W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6135): Unsupported mime audio/evrc
,W/AudioCapabilities( 6135): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6135): Unsupported mime audio/mpeg-L1
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/AudioCapabilities( 6135): Unsupported mime audio/mpeg-L2
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6135): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6135): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6135): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6135): Unsupported mime audio/evrc
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6135): Unsupported mime video/wvc1
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ConnectivityService( 1022): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/VideoCapabilities( 6135): Unsupported mime video/x-ms-wmv
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/GpsLocationProvider( 1022): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/VideoCapabilities( 6135): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6135): Unsupported mime video/wvc1
,W/VideoCapabilities( 6135): Unsupported mime video/x-ms-wmv
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ApplicationPolicy( 1022): updateDataUsageMap
,W/VideoCapabilities( 6135): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6135): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6135): Unsupported mime video/mp43
,W/VideoCapabilities( 6135): Unsupported mime video/sorenson
,W/VideoCapabilities( 6135): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6135): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6135): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6135): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6135): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6135): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1022): Killing 5175:com.google.android.gm/u0a99 (adj 15): empty #31
,I/vclib   ( 6135): onServiceConnected
,W/Babel   ( 6135): Attempted to change video mute state without an active call.
,D/SSRM:n  ( 1022): SIOP:: AP = 290
W/art     ( 6135): Suspending all threads took: 5.863ms
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1022): failed to open /acct/uid_10099/pid_5175/cgroup.procs: No such file or directory
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,W/ActivityManager( 1022): userId = 0, bbcId = -10000,
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/PCWCLIENTTRACE_PushUtil( 5671): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5671): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5671): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5671): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1022): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
,I/splitIntent( 1022): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1022): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1022): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5671): noConnectivity : true
,E/Zygote  ( 6179): MountEmulatedStorage()
E/Zygote  ( 6179): v2
I/libpersona( 6179): KNOX_SDCARD checking this for 10108
I/libpersona( 6179): KNOX_SDCARD not a persona
,I/ActivityManager( 1022): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6179 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6179): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6179): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6179): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6179): TimaSignature is unavailable
,D/ActivityThread( 6179): Added TimaKeyStore provider
,I/wpa_supplicant( 1401): nl80211: Received scan results (4 BSSes),
I/wpa_supplicant( 1401): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1401): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1401): Trying to associate with  'G700'
I/wpa_supplicant( 1401): Re-associate with C0.AA.48
I/wpa_supplicant( 1401): wlan0: State: SCANNING -> ASSOCIATING,
I/wpa_supplicant( 1401): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/WifiMonitor( 1022): didn't find BSSID Trying to associate with SSID 'NG700'
,D/SecContentProvider2( 1022): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1022): mCursor = null
,I/MusicStore( 6179): Database version: 120
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6179): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/wpa_supplicant( 1401): Cmd 35605 not handled
,I/wpa_supplicant( 1401): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1401): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1401): Associated with C0.AA.48
I/wpa_supplicant( 1401): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1401): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1401): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1022): interfaceLinkStateChanged wlan0, false
D/Tethering( 1022): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1022): interfaceLinkStateChanged wlan0, false
D/Tethering( 1022): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1022): interfaceLinkStateChanged wlan0, false
D/SecContentProvider2( 1022): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1022): mCursor = null
,D/Tethering( 1022): interfaceStatusChanged wlan0, false
,D/SecContentProvider2( 1022): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1022): mCursor = null
,I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1022): interfaceLinkStateChanged wlan0, true
D/Tethering( 1022): interfaceStatusChanged wlan0, true
,E/Tethering( 1022): No numeric data
,D/Tethering( 1022): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1022): clearTetheredNotification()
,V/NetworkStats( 1022): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1022): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1022): UpdateStatsForKnox main else ---
,D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
D/HotspotTile( 1177): updateTetherState():false, false
V/NetworkStats( 1022): performPollLocked() took 3ms
,W/ContextImpl( 6179): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6179): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/wpa_supplicant( 1401): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1401): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1401): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1401): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1401): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1401): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1401): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1401): Blacklist: Clear (temp) 
I/wpa_supplicant( 1401): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1022): interfaceLinkStateChanged wlan0, true,
I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, true
D/Tethering( 1022): interfaceStatusChanged wlan0, true
,D/WifiNative-wlan0( 1022): callSECApiVoid - ID [50]
,E/WifiConfigStore( 1022): setLastSelectedConfiguration -1
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/ResourcesManager( 6179): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ResourcesManager( 6179): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ConnectivityService( 1022): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1022): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1022): updateNetworkInfo()
E/WifiConfigStore( 1022): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1022): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/WifiConfigStore( 1022): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  279): Setting iface cfg
,E/WifiStateMachine( 1022): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1022): uri = 20 selection = getPromptCredentialsEnabled
,V/JNIHelp ( 6179): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/SecContentProvider2( 1022): mCursor = null
,E/WifiNative-wlan0( 1022): do suspend false
,D/WifiP2pService( 1022): InactiveState{ what=143375 }
,D/WifiP2pService( 1022): P2pEnabledState{ what=143375 }
,D/SecContentProvider2( 1022): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1022): mCursor = null
,W/ActivityThread( 6179): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6179): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b2c0107: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6179): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6179): GMSCore installation verified
,E/SQLiteLog( 1715): (10) POSIX Error : 11 SQLite Error : 3850
,I/ConfigStore( 6179): Config Database version: 1
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1022): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1022): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1022): getStreamVolume 3 index 70,
,I/MediaRouter( 6179): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6179): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1022): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/dhcpcd  ( 6206): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6206): version 5.5.6 starting
,E/dhcpcd  ( 6206): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6209): MountEmulatedStorage(),
E/Zygote  ( 6209): v2
I/libpersona( 6209): KNOX_SDCARD checking this for 10001
I/libpersona( 6209): KNOX_SDCARD not a persona
,I/SELinux ( 6209): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1022): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6209 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6209): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6209): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GHttpClientFactory( 6179): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/TimaKeyStoreProvider( 6209): TimaSignature is unavailable
,D/ActivityThread( 6209): Added TimaKeyStore provider
,I/dhcpcd  ( 6206): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 6206): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6206): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6206): bssid match
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
I/dhcpcd  ( 6206): wlan0: rebinding lease of 192.168.1.132
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 6179): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1022): Killing 5587:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6232): MountEmulatedStorage(),
,E/Zygote  ( 6232): v2
I/libpersona( 6232): KNOX_SDCARD checking this for 1000
I/libpersona( 6232): KNOX_SDCARD not a persona
I/SELinux ( 6232): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6232): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6232): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6232 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1022): Killing 4155:com.sec.spp.push/u0a32 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6232): TimaSignature is unavailable
,D/ActivityThread( 6232): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 6232): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1022): failed to open /acct/uid_10139/pid_5587/cgroup.procs: No such file or directory
,W/libprocessgroup( 1022): failed to open /acct/uid_10032/pid_4155/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6232): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6232): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
I/DIAGMON_AGENT( 6232): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE,
,I/DIAGMON_AGENT( 6232): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6232): ./extraInfo: <unknown ssid>
W/DIAGMON_AGENT( 6232): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6248): MountEmulatedStorage(),
E/Zygote  ( 6248): v2
I/libpersona( 6248): KNOX_SDCARD checking this for 10008
I/libpersona( 6248): KNOX_SDCARD not a persona
,I/SELinux ( 6248): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1022): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6248 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1022): Killing 5157:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,I/SELinux ( 6248): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6248): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6248): TimaSignature is unavailable
,D/ActivityThread( 6248): Added TimaKeyStore provider
,I/art     (  311): Explicit concurrent mark sweep GC freed 8694(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 700us total 29.945ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 685us total 16.740ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 16.787ms
,W/libprocessgroup( 1022): failed to open /acct/uid_10032/pid_5157/cgroup.procs: No such file or directory
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ActivityManager( 1022): Killing 5255:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3674): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 14 13:18:18 GMT+01:00 2016
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3674): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3674): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3674): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
E/Zygote  ( 6264): MountEmulatedStorage(),
E/Zygote  ( 6264): v2
I/libpersona( 6264): KNOX_SDCARD checking this for 10031
I/libpersona( 6264): KNOX_SDCARD not a persona,
I/SELinux ( 6264): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1022): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6264 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
,I/KLMS-2.5.123: ( 3674): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false,
I/SELinux ( 6264): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/KLMS-2.5.123: ( 3674): StateImplV2(): networkChangeListener().END
,E/SELinux ( 6264): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6264): TimaSignature is unavailable
,D/ActivityThread( 6264): Added TimaKeyStore provider
,I/SO_AGENT( 6264): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5704): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5767): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5767): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 5767): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,W/libprocessgroup( 1022): failed to open /acct/uid_10014/pid_5255/cgroup.procs: No such file or directory
,I/SA      ( 5767): [SLFUCHKMGR] constructor called
,V/AlarmManager( 1022): waitForAlarm result :4
,I/DBG_POLICYDM( 5704): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 5704): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5704): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5704): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 5767): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5767): [OR] == isSIMCardReady false ==
,I/SA      ( 5767): [SCU] == networkStateCheck == false
,I/SA      ( 5767): [OR] onReceive END
,I/ActivityManager( 1022): Killing 5634:com.samsung.helphub/1000 (adj 15): empty #31
,V/DownloadManager( 1231): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1544): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1597): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1544): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1544): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1544): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1544): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1544): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1544): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6281): MountEmulatedStorage(),
E/Zygote  ( 6281): v2
I/libpersona( 6281): KNOX_SDCARD checking this for 10121
,I/libpersona( 6281): KNOX_SDCARD not a persona
I/ActivityManager( 1022): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6281 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 6281): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6281): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6281): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6281): TimaSignature is unavailable
,D/ActivityThread( 6281): Added TimaKeyStore provider
,W/ResourcesManager( 6281): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6281): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6281): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6281): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6281): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6281): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6296): MountEmulatedStorage()
,E/Zygote  ( 6296): v2
I/libpersona( 6296): KNOX_SDCARD checking this for 10141
I/libpersona( 6296): KNOX_SDCARD not a persona
,I/SELinux ( 6296): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1022): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6296 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 6296): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6296): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Killing 5656:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6296): TimaSignature is unavailable
,D/ActivityThread( 6296): Added TimaKeyStore provider
,W/ResourcesManager( 6296): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6296): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6296): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6296): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_5634/cgroup.procs: No such file or directory
,W/libprocessgroup( 1022): failed to open /acct/uid_10087/pid_5656/cgroup.procs: No such file or directory
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/BadgeProvider( 5788): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/BadgeProvider( 5788): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5788): sendNotify, [notify] : null
D/BadgeProvider( 5788): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5788): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5788): update, [UpdateCount] : 1
,D/Launcher.Model( 1480): reloadBadges entered.
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6319): MountEmulatedStorage()
E/Zygote  ( 6319): v2
I/libpersona( 6319): KNOX_SDCARD checking this for 1000
I/libpersona( 6319): KNOX_SDCARD not a persona
I/SELinux ( 6319): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6319): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1022): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6319 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 6319): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6319): TimaSignature is unavailable
,D/ActivityThread( 6319): Added TimaKeyStore provider
,D/SecurityLogAgent( 6319): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6319): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6319): StateMachine : Current State = 1
,D/SecurityLogAgent( 6319): StateMachine : Changed Current State = 1
,I/ActivityManager( 1022): Killing 5270:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/iu.Environment( 1965): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1965): num queued entries: 0
,I/iu.UploadsManager( 1965): num updated entries: 0
,I/iu.SyncManager( 1965): NEXT; no task
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1965): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 55866(2MB) AllocSpace objects, 8(180KB) LOS objects, 33% free, 24MB/36MB, paused 2.730ms total 216.983ms
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6340): MountEmulatedStorage()
I/libpersona( 6340): KNOX_SDCARD checking this for 10032
E/Zygote  ( 6340): v2
I/libpersona( 6340): KNOX_SDCARD not a persona
,I/SELinux ( 6340): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6340): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6340): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6340 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/libprocessgroup( 1022): failed to open /acct/uid_10029/pid_5270/cgroup.procs: No such file or directory
,I/Babel   ( 6135): connection state changed from UNKNOWN to DISCONNECTED
,W/ActivityManager( 1022): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 1022): Killing 5724:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6340): TimaSignature is unavailable
,D/ActivityThread( 6340): Added TimaKeyStore provider
,I/dhcpcd  ( 6206): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,E/SPPClientService( 6340): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6340): [SystemStateMoniter] Current Time : 160015
,E/SPPClientService( 6340): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6340): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 6340): [SystemStateMoniter] No Connect : true
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6340): PushLog.txt file is not deleted.
,D/SPPClientService( 6340): PushLog.txt file is not deleted.
,D/SPPClientService( 6340): ============PushLog. stop!
,E/Zygote  ( 6357): MountEmulatedStorage()
I/ActivityManager( 1022): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6357 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6357): v2
I/libpersona( 6357): KNOX_SDCARD checking this for 10110
I/SELinux ( 6357): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 6357): KNOX_SDCARD not a persona
,I/ActivityManager( 1022): Killing 5752:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
I/SELinux ( 6357): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
E/SELinux ( 6357): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 6206): wlan0: leased 192.168.1.132 for 86400 seconds
,E/SPPClientService( 6340): [[SystemStateMonitorService]] No Active Internet,
,W/libprocessgroup( 1022): failed to open /acct/uid_10148/pid_5724/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6357): TimaSignature is unavailable
,D/ActivityThread( 6357): Added TimaKeyStore provider,
,W/libprocessgroup( 1022): failed to open /acct/uid_10152/pid_5752/cgroup.procs: No such file or directory
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6357): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6357): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6357): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6357):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6357):   adb logcat -s GAv4
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6357): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6357): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6357): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6357): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6357): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/WifiNative-wlan0( 1022): do suspend true
,D/WifiP2pService( 1022): InactiveState{ what=143375 }
,D/WifiP2pService( 1022): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1022): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,E/WifiStateMachine( 1022): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1022): callSECApiInt - ID [210]
,E/ConnectivityService( 1022): updateNetworkInfo()
,D/ConnectivityService( 1022): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1022): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1022): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1022): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1022): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1022): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1022): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null,
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1022): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1022): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1022): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1022): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,I/WifiTrafficPoller( 1022): evaluateTrafficStatsPolling
,E/ConnectivityService( 1022): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1022): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1022): LTETest block dns file not exists
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1022): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/ConnectivityService( 1022): updateNetworkInfo()
I/WifiTrafficPoller( 1022): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1022): mBoosterFLAG : 0
I/WifiTrafficPoller( 1022): current booster mode : FullMode
E/WifiStateMachine( 1022): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine( 1022): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WifiNative-wlan0( 1022): callSECApiVoid - ID [212]
E/ConnectivityService( 1022): updateNetworkInfo()
,D/ConnectivityService( 1022): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1022): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
D/ConnectivityService( 1022): rematching NetworkAgentInfo [WIFI () - 503]
I/System.out( 1022): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 1022):    accepting network in place of null
,D/WIFI_P2P( 1022): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1451): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1451): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1022): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,E/CSLegacyTypeTracker( 1022): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1022): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1022): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1022): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 1022): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1022): MasterInitialState.processMessage what=3
V/NetworkStats( 1022): updateIfacesLocked()
V/NetworkStats( 1022): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/ConnectivityService( 1022): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/EntConnectivity( 1022): Not allowed due to - mEnabled false - primarySimSlot false
D/NetworkStatsFactory( 1022): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1022): UpdateStatsForKnox main else ---
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,V/NetworkStats( 1022): performPollLocked() took 6ms
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
V/NetworkStats( 1022): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/System.out( 1022): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 14 Jan 2016 12:18:20 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452773900144], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452773900125]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Don't send network conditions - lacking user consent.
D/ConnectivityService( 1022): Validated NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Validated
D/ConnectivityService( 1022): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1022): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1022): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1022): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1177): EthernetConnected: false,
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType(),
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0,
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,I/WebViewFactory( 6357): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6357): Time to load native libraries: 2 ms (timestamps 625-627)
I/LibraryLoader( 6357): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6357): Binding Chromium to main looper Looper (main, tid 1) {3300cf3c}
,I/LibraryLoader( 6357): Expected native library version number "",actual native library version number ""
,I/chromium( 6357): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6357): Initializing chromium process, singleProcess=true
,W/art     ( 6357): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6357): ApplicationContext is null in ApplicationStatus
,W/chromium( 6357): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6357): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6357): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6357): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6357): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6357): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6357): Local Branch: 
I/Adreno-EGL( 6357): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6357): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6357):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 6357): Requires BLUETOOTH permission
,I/NSApplication( 6357): Starting up...
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1022): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6439 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6439): MountEmulatedStorage()
E/Zygote  ( 6439): v2
I/libpersona( 6439): KNOX_SDCARD checking this for 10077
I/libpersona( 6439): KNOX_SDCARD not a persona
,I/SELinux ( 6439): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6439): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6439): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Killing 5623:com.android.mms/u0a41 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6439): TimaSignature is unavailable
,D/ActivityThread( 6439): Added TimaKeyStore provider
,D/CountryDetector( 1022): No listener is left
,D/WaitQueueForNetworkActivate( 5973): notifyNetworkActivated
,W/ContextImpl( 5973): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1022): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService( 1022): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 6179): type=WIFI subType= reason=null isConnected=true
,W/libprocessgroup( 1022): failed to open /acct/uid_10041/pid_5623/cgroup.procs: No such file or directory
,D/GpsLocationProvider( 1022): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1022): mCursor = null
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5973): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5973): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5973): exit::IDLE
D/InitializeManagerStateMachine( 5973): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5973): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5973): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5973): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5973): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5973): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5973): entry::SUCCESS
D/hcjo    ( 5973): AutoUpdateManager:INITCHECK:onInitializeSuccess
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2104): Starting #10
,D/hcjo    ( 5973): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5973): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/Hs20UtilService( 2104): Message received 5007
,D/InitializeManagerStateMachine( 5973): exit::SUCCESS
D/InitializeManagerStateMachine( 5973): entry::IDLE
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null
,I/ActivityManager( 1022): Killing 5806:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2104): Starting #11
,I/Hs20UtilService( 2104): Message received 5007
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2104): Starting #12
,I/Hs20UtilService( 2104): Message received 5007
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2104): Starting #13
,I/Hs20UtilService( 2104): Message received 5007
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/WifiStateMachine( 1022): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1022): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1022): mCursor = null
,D/SecContentProvider2( 1022): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1022): mCursor = null
,D/SecContentProvider2( 1022): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1022): mCursor = null
,D/SecContentProvider2( 1022): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1022): mCursor = null
,D/SecContentProvider2( 1022): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1022): mCursor = null
,D/SecContentProvider2( 1022): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1022): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5671): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5671): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5671): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5671): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1022): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
,I/splitIntent( 1022): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1022): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
,I/splitIntent( 1022): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6179): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/libprocessgroup( 1022): failed to open /acct/uid_10042/pid_5806/cgroup.procs: No such file or directory
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT( 6232): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6232): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6232): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6232): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService( 1022): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1022
,D/SRIB_DCS( 1177): log_dcs ThreadedRenderer::initialize entered! 
,I/DBG_POLICYDM( 5704): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5704): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5704): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5704): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5704): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5704): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6248): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6248): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 3674): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 14 13:18:20 GMT+01:00 2016
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3674): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3674): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3674): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3674): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3674): StateImplV2(): networkChangeListener().START
,I/DBG_POLICYDM( 5704): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3674): NetworkChangeOperations(): uploadRequestLog().START 
,I/art     ( 1715): Explicit concurrent mark sweep GC freed 22167(1284KB) AllocSpace objects, 5(101KB) LOS objects, 40% free, 7MB/12MB, paused 1.173ms total 48.609ms
,I/DBG_POLICYDM( 5704): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5704): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5704): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/KLMS-2.5.123: ( 3674): NetworkChangeOperations(): uploadRequestLog().END 
,D/ConnectivityService( 1022): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SA      ( 5767): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5767): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
D/GCM     ( 1715): Connected
I/SA      ( 5767): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/KLMS-2.5.123: ( 3674): StateImplV2(): networkChangeListener().END
,I/SA      ( 5767): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): onDestroy()
I/SA      ( 5767): [OR] == isSIMCardReady false ==
,I/DBG_POLICYDM( 5704): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 5767): [SCU] == networkStateCheck == true
,I/SA      ( 5767): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5767): isChinaCountryCode : false
I/SA      ( 5767): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5767): [OR] == networkStateCheck true ==
,D/GCM     ( 1715): Message class com.google.f.a.a.p
,I/SA      ( 5767): [OR] GetMyCountryZoneTask
I/SA      ( 5767): [OR] onReceive END
,V/DownloadManager( 1231): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5767): [SRS] prepareGetMyCountryZone
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 5704): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5704): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5704): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5704): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,D/accuweather( 1544): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5704): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5704): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5704): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/SA      ( 5767): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5767): [SSP] query invoked
,I/DBG_POLICYDM( 5704): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,D/daemonapp( 1597): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1544): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
I/DBG_POLICYDM( 5704): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/accuweather( 1544): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1544): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1544): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1544): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/DBG_POLICYDM( 5704): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/accuweather( 1544): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/SecContentProvider2( 1022): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1022): mCursor = null
,I/SA      ( 5767): [TPMU] GetMccFromDB : null
I/SA      ( 5767): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5767): [TPM] isNoProxy(default) : true
,D/QuickConnect( 6281): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6281): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6281): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,E/File    ( 5767): fail readDirectory() errno=2
,I/DBG_POLICYDM( 5704): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
I/DBG_POLICYDM( 5704): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/SecurityLogAgent( 6319): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6319): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6319): StateMachine : Current State = 1
,D/SecurityLogAgent( 6319): StateMachine : Changed Current State = 1
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ConnectivityService( 1022): reportBadNetwork(NetworkAgentInfo [WIFI () - 503]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
I/System.out( 1022): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1022): Tagging socket 364 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1022, getuid(): 1000
,I/iu.Environment( 1965): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1965): num queued entries: 0
,I/iu.UploadsManager( 1965): num updated entries: 0
,I/qtaguid ( 1022): Untagging socket 364
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 14 Jan 2016 12:18:21 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452773901191], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452773901173]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Validated
,D/ConnectivityService( 1022): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1022): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1022): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1022): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,I/iu.SyncManager( 1965): NEXT; no task
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1965): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1965): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6340): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6340): [SystemStateMoniter] Current Time : 161658
,E/SPPClientService( 6340): [SystemStateMoniter] No Connect : false
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 6135): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6135): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 6135): (HTTPLog)-Static: isShipBuild true
I/System.out( 6135): (HTTPLog)-Thread-1042-406395089: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6135): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10102
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps,
,D/hcjo    ( 5973): AutoUpdateManager:IDLE:execute
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/InitializeManagerStateMachine( 5973): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5973): exit::IDLE
D/InitializeManagerStateMachine( 5973): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5973): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5973): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5973): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5973): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5973): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5973): entry::SUCCESS
D/hcjo    ( 5973): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/hcjo    ( 5973): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5973): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5973): exit::SUCCESS
,D/InitializeManagerStateMachine( 5973): entry::IDLE
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 6135): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
,I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/Kids    ( 1965): [AccountUtils] Account not ready
W/Kids    ( 1965): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1965): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1965): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1965): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1965): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1965): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1965): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1965): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1965): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1965): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1965): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1965): 	at java.lang.Thread.run(Thread.java:818)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 6135): connection state changed from DISCONNECTED to CONNECTED
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/SA      ( 5767): [RC New] Execute method=[GET] start
,I/SA      ( 5767): [RC New] Security=[true]
,I/System.out( 5767): Thread-970(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5767): Thread-970(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5767): Thread-970(ApacheHTTPLog):isShipBuild true
I/System.out( 5767): Thread-970(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5767): Thread-970(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10036
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/SA      ( 5767): [RC New] [v2liruge] api execute + 638
,I/SA      ( 5767): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 5767): AsyncTask #1 calls detatch()
,I/SA      ( 5767): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5767): [OCP] update openData : PL
,I/SA      ( 5767): [TPMU] getNetworkMcc : 
,I/SA      ( 5767): [SCU] saveMccToPreferece Start
,I/SA      ( 5767): [SCU] RegionMCC : 260
I/SA      ( 5767): [SSP] query invoked
,I/SA      ( 5767): [TPMU] GetMccFromDB : null
,I/SA      ( 5767): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5767): [SCU] saveMccToPreferece End
,I/SA      ( 5767): [RC New] executeRequest [v2liruge] end. 693
I/SA      ( 5767): [RC New] Execute end
,I/SA      ( 5767): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5767): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 6206): wlan0: sending IPv6 Router Solicitation
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1022): waitForAlarm result :4
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1022): Do not check CP during LCD off.,
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/GCM     ( 1715): Connected
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/GCM     ( 1715): Message class com.google.f.a.a.p
,I/MusicLeanback( 6179): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6179): Stop autocaching.
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 4402): callingUid 10011, callindPid: 4402
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/GmsUtils( 6179): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6179): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push,
,I/SurfaceFlinger(  258): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  258): id=14 Removed Uoast (-2/9),
,D/PowerManagerService( 1022): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1022) eventTime = 164753
,D/PowerManagerService( 1022): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1022 (0x0)
D/PowerManagerService( 1022): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1022, ws=WorkSource{10049}) (elapsedTime=3464)
,E/SMD     (  289): DCD OFF,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5671): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5671): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5671): [GetString-S]
,I/ReactiveServiceManager( 5671): Supported : 1
,D/QSEECOMAPI: ( 1022): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1022): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1022): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1022): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1022): QSEECom_shutdown_app, app_id = 11
E/terrier ( 1022): handleString: Failed to handle string(-4)
,E/terrier ( 1022): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 5671): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5671): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5671): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5671): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5671): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5671): [ensureRegistration] - No Samsung account
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,I/dhcpcd  ( 6206): wlan0: sending IPv6 Router Solicitation
,D/SSRM:n  ( 1022): SIOP:: AP = 310
,E/Watchdog( 1022): !@Sync 5
,I/jxcore-log( 6078): Test app app.js loaded
I/jxcore-log( 6078): 
,I/Choreographer( 6078): Skipped 662 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6078): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/AlarmManager( 1022): waitForAlarm result :4
,E/SMD     (  289): DCD OFF
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5340): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5340): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5340): [1] 5.onFinished: Scheduling replication attempt 5.
,I/dhcpcd  ( 6206): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6206): wlan0: no IPv6 Routers available
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5973): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5973): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5973): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5973): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5973): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5973): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5973): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5973): entry::IDLE
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5973): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5973): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5973): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5973): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5973): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5973): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5973): entry::IDLE
,V/AlarmManager( 1022): waitForAlarm result :4
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  289): DCD OFF
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 41521(2MB) AllocSpace objects, 7(116KB) LOS objects, 33% free, 24MB/36MB, paused 2.437ms total 173.041ms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.youtube
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6510): MountEmulatedStorage()
I/libpersona( 6510): KNOX_SDCARD checking this for 10161
E/Zygote  ( 6510): v2
I/libpersona( 6510): KNOX_SDCARD not a persona
I/SELinux ( 6510): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6510 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6510): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6510): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6510): TimaSignature is unavailable
,D/ActivityThread( 6510): Added TimaKeyStore provider
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Batterystats( 1965): User is not opted-in to Usage & Diagnostics.
,W/ResourcesManager( 6510): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6510): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6510): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6510): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6510): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3f12bd4b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6510): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 6510): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6510): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/YouTube MDX( 6510): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 6538): ----------------------------------------------------
I/dex2oat ( 6538): <SS>: S T A R T I N G . . .
I/dex2oat ( 6538): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 6538): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads912366237.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads912366237.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6510): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/dex2oat ( 6538): dex2oat took 72.158ms (threads: 4)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6510): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 6510): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6510): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 6510): Found 10011
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6510): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/AndroidHttpClient( 6510): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
,D/AndroidHttpClient( 6510): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 6510): Thread-1148(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6510): Thread-1148(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6510): Thread-1148(ApacheHTTPLog):isShipBuild true
I/System.out( 6510): Thread-1148(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6510): Thread-1148(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10161
,I/System.out( 6510): Thread-1148 calls detatch()
,E/SMD     (  289): DCD OFF
,I/System.out( 6510): Thread-1137(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6510): Thread-1137(ApacheHTTPLog):isShipBuild true
I/System.out( 6510): Thread-1137(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6510): Thread-1137(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10161
,I/qtaguid ( 6510): Tagging socket 51 with tag 0{0,0} for uid -1, pid: 6510, getuid(): 10161
,I/qtaguid ( 6510): Untagging socket 51
,I/System.out( 6510): Thread-1137 calls detatch()
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1022): Killing 5827:com.wsomacp/u0a23 (adj 15): empty #31
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1715): Vacuum at: now=1452773915453 tag=VacuumService
,W/libprocessgroup( 1022): failed to open /acct/uid_10023/pid_5827/cgroup.procs: No such file or directory
,I/GoogleURLConnFactory( 1715): Using platform SSLCertificateSocketFactory
,W/Uploader( 1715): No account for auth token provided
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1715): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1715): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1715): (HTTPLog)-Static: isShipBuild true
I/System.out( 1715): (HTTPLog)-Thread-206-885933339: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1715): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,I/System.out( 1715): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1715): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1715, getuid(): 10011
,I/qtaguid ( 1715): Tagging socket 61 with tag 120100000000{4609,0} for uid -1, pid: 1715, getuid(): 10011
,W/Uploader( 1715): No account for auth token provided
,I/System.out( 1715): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1715): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1715, getuid(): 10011
,W/Uploader( 1715): No account for auth token provided
,I/System.out( 1715): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1715): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1715, getuid(): 10011
,W/Uploader( 1715): No account for auth token provided
,I/System.out( 1715): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1715): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1715, getuid(): 10011
,W/Uploader( 1715):  no longer exists, so no auth token.
,I/System.out( 1715): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1715): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1715, getuid(): 10011
,W/Uploader( 1715): No account for auth token provided
,I/System.out( 1715): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1715): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1715, getuid(): 10011
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,E/Uploader( 1715): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1715): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1715): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1715): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1715): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1715): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1715): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1715): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1715): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1715): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1715): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1715): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1715): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,I/System.out( 1715): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1715): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1715, getuid(): 10011
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1715): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:n  ( 1022): SIOP:: AP = 290
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1022): [PWL] Off : 105s ago
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1022): Do not check CP during LCD off.
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1022): waitForAlarm result :4
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1022): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1022): waitForAlarm result :4
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5340): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5340): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5340): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged,
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/Watchdog( 1022): !@Sync 6
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :8,
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1022): Do not check CP during LCD off.
,V/AlarmManager( 1022): waitForAlarm result :4
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
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,I/PowerManagerService( 1022): [PWL] Off : 140s ago
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1022): Do not check CP during LCD off.
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,E/Watchdog( 1022): !@Sync 7
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1022): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1022): !@Sync 8
,I/PowerManagerService( 1022): [PWL] Off : 180s ago
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :8
,E/SMD     (  289): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1022): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1022): Do not check CP during LCD off.
,V/AlarmManager( 1022): waitForAlarm result :4
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
,I/BooksSync( 6001): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6001): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
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
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6001): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6001): Soft error
E/BooksSync( 6001): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6001): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6001): Sync error
E/BooksSync( 6001): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6001): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6001): Finished books sync
,D/SyncManager( 1022): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 284611, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1022): mCursor = null
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1022): !@Sync 9,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged,
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1022): [PWL] Off : 225s ago
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1022): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :4
,D/TimaService( 1022): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1022): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1022): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1022): initializing...
I/TLC_TIMA_PKM_initialize( 1022): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1022): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1022): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1022): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1022): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1022): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1022): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1022): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1022): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1022): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1022): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1022): Trustlet response is completed
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1022): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1022): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1022): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1022): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/Watchdog( 1022): !@Sync 10
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1022): Do not check CP during LCD off.,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,I/jxcore-log( 6078): --= Surplus to requirements =--
I/jxcore-log( 6078): 
,I/jxcore-log( 6078): ****TEST TOOK:  ms ****
I/jxcore-log( 6078): 
I/jxcore-log( 6078): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6078): 
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,D/AndroidRuntime( 6682): 
D/AndroidRuntime( 6682): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6682): CheckJNI is OFF
D/AndroidRuntime( 6682): readGMSProperty: start
D/AndroidRuntime( 6682): readGMSProperty: already setted!!
D/AndroidRuntime( 6682): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6682): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6682): readGMSProperty: end
D/AndroidRuntime( 6682): addProductProperty: start
,E/AffinityControl( 6682): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6682): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1022): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1022): START PACKAGE DELETE: observer{233993904}
D/PackageManager( 1022): pkg{<packageName>}
,D/PackageManager( 1022): user{0}
D/PackageManager( 1022): caller{2000}
D/PackageManager( 1022): flags{3}
D/PersonaManagerService( 1022): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1022): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1022): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager( 1022): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1022): !@killApplicatoin: 10338, uninstall pkg
D/PackageManager( 1022): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1022): deletePackage- pkg:com.test.thalitest, edmuserId:0,
D/PackageManagerService( 1022): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1022): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1022): getApplicationUninstallationEnabled :  enabled true
,I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
,I/ActivityManager( 1022): Killing 6078:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1022): Skipping PackageSetting{1891196b com.example.hello/10346} due to missing metadata
,I/WindowState( 1022): WIN DEATH: Window{3cf16684 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1022): Focus left window: 6078
,I/ActivityManager( 1022):   Force finishing activity ActivityRecord{28a84342 u0 com.test.thalitest/.MainActivity t20}
,W/ActivityManager( 1022): Spurious death for ProcessRecord{c865929 6078:com.test.thalitest/u0a338}, curProc for 6078: null
,D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,D/InputDispatcher( 1022): Focused application released
,I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
,W/ActivityManager( 1022): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 4003): Explicit concurrent mark sweep GC freed 3116(187KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 774us total 31.297ms
,I/art     ( 5956): Explicit concurrent mark sweep GC freed 95(15KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 706us total 34.866ms
,I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1770): mOCRHelper is null
,W/GeofencerStateMachine( 1630): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.5.123: ( 3674): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 14 13:21:19 GMT+01:00 2016
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3674): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1022): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
,I/splitIntent( 1022): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1022): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1022): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): onCreate()
I/KLMS-2.5.123: ( 3674): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/libpersona( 6695): KNOX_SDCARD checking this for 10090
E/Zygote  ( 6695): MountEmulatedStorage()
I/libpersona( 6695): KNOX_SDCARD not a persona
E/Zygote  ( 6695): v2
I/SELinux ( 6695): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6695): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6695): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6695 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3674): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): PACKAGE_REMOVED
D/EnterpriseDeviceManagerService( 1022): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1022): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1022): no available spell checker services found
,D/TimaKeyStoreProvider( 6695): TimaSignature is unavailable
,D/ActivityThread( 6695): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): listeningToPackageRemoved().START
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1022): mCursor = null
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RegisteredServicesCache( 1443): empty dynamic service
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 47231(3MB) AllocSpace objects, 75(1209KB) LOS objects, 33% free, 24MB/36MB, paused 5.891ms total 190.741ms
,I/art     ( 1022): WaitForGcToComplete blocked for 119.749ms for cause Explicit
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 6695): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6695): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6695): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6695): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 6695): ElmAgentService : onCreate()
,D/elm:15121( 6695): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 6695): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6695): MDMBridge.getInstance()
D/elm:15121( 6695): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 6695): MDMBridge.getAllLicenseInfoFromSDK()
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 6695): ElmAgentService : onDestroy().
,I/ActivityManager( 1022): Killing 4962:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): onDestroy()
,D/RCPManagerService( 1022): PackageReceiver onReceive()
I/HarmonyEASService( 1022): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1022): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/ResourceType( 1022): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 10688(508KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 3.127ms total 175.420ms
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1022): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 1022): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1022): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1022): delete codoeFile: 
,D/AASAuninstall( 1022): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
,I/AASA_removePackage( 1022): UID=10338 Target=com.test.thalitest
,D/PackageManager( 1022): result of delete: 1{233993904}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AndroidRuntime( 6682): Shutting down VM
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService( 1022): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/UsbSettingsManager( 1022): clearDefaults: com.test.thalitest
,D/JobSchedulerService( 1022): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1022): uID is 10338
V/EnterpriseBillingPolicy( 1022): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - enter
I/ServiceManager(  325): Waiting for service AtCmdFwd...
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - personal application - profile null
,V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - end - null
,I/CrashAnrDetector( 1022): onPackageRemoved : com.test.thalitest
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,W/libprocessgroup( 1022): failed to open /acct/uid_10039/pid_4962/cgroup.procs: No such file or directory
,D/TaskPersister( 1022): removeObsoleteFile: deleting file=20_task.xml
,V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1022): uID is 10338
V/EnterpriseBillingPolicy( 1022): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - enter
,D/SSRM:aZ ( 1022): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - end - null
,I/PCWCLIENTTRACE_PushUtil( 5671): SPPPushClient is installed : true
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_PushUtil( 5671): sales region : global
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
I/PCWCLIENTTRACE_PushUtil( 5671): getPushTypeList : [SPP, GCM]
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
I/PCWCLIENTTRACE_SYSTEMReceiver( 5671): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6712): MountEmulatedStorage()
I/libpersona( 6712): KNOX_SDCARD checking this for 10029
E/Zygote  ( 6712): v2
I/libpersona( 6712): KNOX_SDCARD not a persona
I/SELinux ( 6712): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6712): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6712): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6712 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6712): TimaSignature is unavailable
,D/ActivityThread( 6712): Added TimaKeyStore provider,
,E/SMD     (  289): DCD OFF
,I/FeatureConfig( 6712): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/SA      ( 5767): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5767): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager( 1022): Killing 5846:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6712): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6712): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6712): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/Zygote  ( 6730): MountEmulatedStorage(),
E/Zygote  ( 6730): v2
I/libpersona( 6730): KNOX_SDCARD checking this for 10039
I/libpersona( 6730): KNOX_SDCARD not a persona
,I/SELinux ( 6730): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1022): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6730 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 6730): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6730): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 6712): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6712): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6712): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/art     (  311): Explicit concurrent mark sweep GC freed 8686(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 749us total 21.338ms,
,W/ResourcesManager( 6712): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 659us total 16.693ms
,W/ResourcesManager( 6712): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6730): TimaSignature is unavailable
,D/ActivityThread( 6730): Added TimaKeyStore provider
,W/ResourcesManager( 6712): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 16.927ms
,W/ResourcesManager( 6730): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6730): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6730): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6730): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6730): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6730): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6730): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/art     ( 6682): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/ResourcesManager( 6712): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6712): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/libprocessgroup( 1022): failed to open /acct/uid_10048/pid_5846/cgroup.procs: No such file or directory
,W/ResourcesManager( 6712): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6712): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6712): system/finder_cp/cpdata.xml file not found
,E/SQLiteLog( 6730): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6730): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase( 6730): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6730): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6730): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6730): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase( 6730): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase( 6730): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6730): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6730): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6730): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6730): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6730): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6730): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6730): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6730): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6730): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/NearbySource( 6730): Nearby Source Create!
,D/NearbyContext( 6730): Nearby Context Create!
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6730): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 6730): Samsung link source created

```
