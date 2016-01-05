#### Test 54968200254eab2_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  289): DCD OFF
,D/AndroidRuntime( 6091): 
D/AndroidRuntime( 6091): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6091): CheckJNI is OFF
D/AndroidRuntime( 6091): readGMSProperty: start
D/AndroidRuntime( 6091): readGMSProperty: already setted!!
D/AndroidRuntime( 6091): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6091): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6091): readGMSProperty: end
D/AndroidRuntime( 6091): addProductProperty: start
E/AffinityControl( 6091): AffinityControl: registerfunction enter
D/AndroidRuntime( 6091): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
W/ActivityManager( 1015): mDVFSHelper.acquire()
D/FocusedStackFrame( 1015): Set to : 0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1015): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1015): *FMB* installDecor flags : 25362712
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1015): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6103 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/libpersona( 6103): KNOX_SDCARD checking this for 10338
D/InputDispatcher( 1015): Focused application set to: xxxx
I/libpersona( 6103): KNOX_SDCARD not a persona
D/InputDispatcher( 1015): Focus left window: 1479
E/Zygote  ( 6103): MountEmulatedStorage()
E/Zygote  ( 6103): v2
D/AndroidRuntime( 6091): Shutting down VM
I/SELinux ( 6103): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6103): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6103): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, uhalitest
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6103): TimaSignature is unavailable
D/ActivityThread( 6103): Added TimaKeyStore provider
V/WindowManager( 1015): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1015): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1015):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
D/Launcher( 1479): onTrimMemory. Level: 20
V/ActivityThread( 1479): updateVisibility : ActivityRecord{271a783f token=android.os.BinderProxy@3c9921bb {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
V/AlarmManager( 1015): waitForAlarm result :4
I/BooksSync( 6025): Starting books sync for 61035162, extras: ade
I/BooksConfig( 6025): GmsCore Version = 7.8.99 (2134222-434)
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
I/WebViewFactory( 6103): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/LibraryLoader( 6103): Time to load native libraries: 2 ms (timestamps 5287-5289)
I/LibraryLoader( 6103): Expected native library version number "",actual native library version number ""
I/GLSUser ( 1768): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1768): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1768): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1768): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/art     ( 6091): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
V/GLSActivity( 1768): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/WebViewChromiumFactoryProvider( 6103): Binding Chromium to main looper Looper (main, tid 1) {3912b014}
I/LibraryLoader( 6103): Expected native library version number "",actual native library version number ""
I/chromium( 6103): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
I/BrowserStartupController( 6103): Initializing chromium process, singleProcess=true
W/art     ( 6103): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6103): ApplicationContext is null in ApplicationStatus
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/GLSUser ( 1768): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1768): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1768): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1768): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1768): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/chromium( 6103): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6103): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6103): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/BooksAccountManager( 6025): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
I/Adreno-EGL( 6103): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6103): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6103): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6103): Local Branch: 
I/Adreno-EGL( 6103): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6103): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6103):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
E/BooksSync( 6025): Soft error
E/BooksSync( 6025): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6025): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6025): Sync error
E/BooksSync( 6025): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6025): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6025): Finished books sync
D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 155203, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
W/art     ( 6103): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6103): onDetachedFromWindow called when already detached. Ignoring
W/ActivityManager( 1015): Activity pause timeout for ActivityRecord{92a0633 u0 com.test.thalitest/.MainActivity t20}
D/PhoneWindow( 6103): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6103): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6103): CordovaWebView is running on device made by: samsung
W/art     ( 6103): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6103): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6103): Render dirty regions requested: true
D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
W/chromium( 6103): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6103): updateVisibility : ActivityRecord{315e7529 token=android.os.BinderProxy@8bfc5f3 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 6103): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6103): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1015): Focus entered window: 6103
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6103): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6103): Initialized EGL, version 1.4
D/OpenGLRenderer( 6103): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6103): Enabling debug mode 0
D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1176): Icon Only
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/PanelView( 1176): There is/are notification(s) 
I/ActivityManager( 1015): Displayed Component not be shown by security: +737ms (total +39s365ms)
W/ActivityManager( 1015): mDVFSHelper.release()
W/IInputConnectionWrapper( 6103): showStatusIcon on inactive InputConnection
I/Timeline( 6103): Timeline: Activity_idle id: android.os.BinderProxy@8bfc5f3 time:155877
I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{92a0633 u0 com.test.thalitest/.MainActivity t20} time:155877
I/SurfaceFlinger(  258): id=12 Removed uhalitest (7/9)
I/SurfaceFlinger(  258): id=12 Removed uhalitest (-2/9)
I/SamsungIME( 1859): getCurrentCandidateView
D/SamsungIME( 1859): Dismiss ExpandCandiate
W/BindingManager( 6103): Cannot call determinedVisibility() - never saw a connection for the pid: 6103
I/SamsungIME( 1859): getDebugLevel  : 0x4f4c
I/SamsungIME( 1859): getDebugLevel  : 0x4f4c
I/SamsungIME( 1859): KeybaordView init() : load resources
I/SamsungIME( 1859): getCurrentKeyboard
I/SamsungIME( 1859): getTextKeyboard
D/JsMessageQueue( 6103): Set native->JS mode to OnlineEventsBridgeMode
D/SamsungIME( 1859): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 6103): JniHelper::setJavaVM(0xb8191448), pthread_self() = -1200710568
D/JX-Cordova( 6103): jxcore cordova android initializing
D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2639): Disconnected process message: 10
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,W/jxcore-log( 6103): Initializing JXcore engine,
W/jxcore-log( 6103): JXcore engine is ready
,W/jxcore-log( 6103): Starting JXcore engine
,E/audit   ( 1856): type=1400 msg=audit(1451954422.056:205): avc:  denied  { ioctl } for  pid=6103 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1856):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1856): type=1300 msg=audit(1451954422.056:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=bec29d58 items=0 ppid=304 ppcomm=main pid=6103 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1856): type=1320 msg=audit(1451954422.056:205): 
,W/jxcore-log( 6103): Platform android
W/jxcore-log( 6103): 
W/jxcore-log( 6103): Process ARCH arm
W/jxcore-log( 6103): 
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/jxcore-log( 6103): JXcore Cordova bridge is ready!
I/jxcore-log( 6103): 
,W/jxcore-log( 6103): JXcore engine is started
,I/Choreographer( 6103): Skipped 134 frames!  The application may be doing too much work on its main thread.
I/chromium( 6103): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/jxcore-log( 6103): Toggling radios to true,
I/jxcore-log( 6103): 
,D/BluetoothAdapter( 6103): enable(),
,D/BluetoothAdapter( 6103): enable(): BT is already enabled..!,
,D/SecContentProvider( 1015): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1015): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1015): mCursor = null
,D/WifiService( 1015): setWifiEnabled: true pid=6103, uid=10338
,W/ActivityManager( 1015): Permission Denial: getCurrentUser() from pid=6103, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1015): Failed getting userId using ActivityManagerNative,
W/WifiService( 1015): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6103, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1015): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1015): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1015): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1015): 	,at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1015): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1015): name = wifi_on
,I/WifiService( 1015): disconnect: pid=6103, uid=10338
,I/wpa_supplicant( 1385): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6103): Radios toggled
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): Got Device Bluetooth address: 08:EC:A9:50:75:41
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): Perf Test app loaded loaded
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): check test folder
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): found test : ./testFindPeers.js
I/jxcore-log( 6103): 
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1385): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1385): wlan0: State: COMPLETED -> DISCONNECTED,
I/wpa_supplicant( 1385): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 1385): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1385): wlan0: State: DISCONNECTED -> DISCONNECTED
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
E/wpa_supplicant( 1385): Cmd 35605 not handled
,D/Tethering( 1015): InitialState.processMessage what=4
E/WifiStateMachine( 1015): WifiStateMachine: Leaving Connected state
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1385): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1385): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1385): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1385): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1385): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1385): First Scan Start
I/wpa_supplicant( 1385): Scan requested (ret=0) - scan timeout 30 seconds
,E/Tethering( 1015): No numeric data
D/Tethering( 1015): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering( 1015): clearTetheredNotification()
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiNative-wlan0( 1015): do suspend true
D/WifiP2pService( 1015): InactiveState{ what=143375 }
D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,D/CommandListener(  279): Clearing all IP addresses on wlan0
V/NativeCrypto( 1768): Read error: ssl=0xb86a9798: I/O error during system call, Connection timed out
I/jxcore-log( 6103): found test : ./testSendData.js
I/jxcore-log( 6103): 
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
E/ConnectivityService( 1015): updateNetworkInfo()
E/WifiStateMachine( 1015): Start Disconnecting Watchdog 1
V/NativeCrypto( 1768): SSL shutdown failed: ssl=0xb86a9798: I/O error during system call, Broken pipe
I/wpa_supplicant( 1385): wlan0: Setting scan request: 0 sec 0 usec
I/rmt_storage(  268): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb75527c8
I/rmt_storage(  268): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  268): wakelock acquired: 1, error no: 42
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1219155832)
,D/ConnectivityService( 1015): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1015): Tagging socket 347 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
E/WifiNative-wlan0( 1015): do suspend true
I/qtaguid ( 1015): Untagging socket 347
V/NetworkStats( 1015): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit,
D/WifiP2pService( 1015): InactiveState{ what=143375 }
D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
D/HotspotTile( 1176): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1176): updateTetherState():false, false
D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1682): Starting #8
I/Hs20UtilService( 1682): Message received 5007
,D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/NearbySettings( 1308): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1308): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1308): MountReceiver.mPrefHandler - 7002
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1219155832) wakelock released: 1, error no: 0
I/rmt_storage(  268): 
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
I/rmt_storage(  268): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb75527c8
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener(  279): Clearing all IP addresses on wlan0
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/ConnectivityService( 1015): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1015): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1015): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 1015): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1015): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
V/NetworkStats( 1015): performPollLocked() took 75ms
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Validated
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524292
D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1444): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1444): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
D/WifiNetworkAgent( 1015): NetworkAgent: NetworkAgent channel lost
D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/ConnectivityService( 1015): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): doQuit - quitNow()
D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/Tethering( 1015): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1015): MasterInitialState.processMessage what=3
V/NetworkStats( 1015): updateIfacesLocked()
V/NetworkStats( 1015): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
D/StatusBar.NetworkController( 1176): EthernetConnected: false
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): performPollLocked() took 5ms
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/Hs20UtilService( 1682): Starting #9
I/Hs20UtilService( 1682): Message received 5007
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
I/Choreographer( 6103): Skipped 109 frames!  The application may be doing too much work on its main thread.
I/chromium( 6103): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1308): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1308): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1308): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
E/SMD     (  289): DCD OFF
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneApp( 1444): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1444): FileWriteThread : threadType = 3
,D/PhoneApp( 1444): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1444): FileWriteThread : threadType = 3,
D/PhoneApp( 1444): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1444): FileWriteThread : threadType = 3,
D/PhoneApp( 1444): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1444): FileWriteThread : threadType = 3,
D/PhoneApp( 1444): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1444): FileWriteThread : threadType = 3
,D/PhoneApp( 1444): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1444): FileWriteThread : threadType = 3
,D/PhoneApp( 1444): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1444): FileWriteThread : threadType = 3
,D/PhoneApp( 1444): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1444): FileWriteThread : threadType = 3
,D/PhoneApp( 1444): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1444): FileWriteThread : threadType = 3
,D/PhoneApp( 1444): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1444): FileWriteThread : threadType = 3
,D/PhoneApp( 1444): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1444): FileWriteThread : threadType = 3
,D/PhoneApp( 1444): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1444): FileWriteThread : threadType = 3
,D/PhoneApp( 1444): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1444): FileWriteThread : threadType = 3
,D/PhoneApp( 1444): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1444): FileWriteThread : threadType = 3
,D/PhoneApp( 1444): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1444): FileWriteThread : threadType = 3
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,I/ApplicationPolicy( 1015): updateDataUsageMap
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 5682): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5682): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5682): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5682): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1015): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1015): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1015): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5682): noConnectivity : true
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6179): MountEmulatedStorage()
I/libpersona( 6179): KNOX_SDCARD checking this for 10108
E/Zygote  ( 6179): v2
I/libpersona( 6179): KNOX_SDCARD not a persona
I/SELinux ( 6179): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6179 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6179): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6179): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6179): TimaSignature is unavailable
,D/ActivityThread( 6179): Added TimaKeyStore provider
,I/MusicStore( 6179): Database version: 120
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6179): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/wpa_supplicant( 1385): nl80211: Received scan results (7 BSSes)
,I/wpa_supplicant( 1385): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1385): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1385): Trying to associate with  'G700'
I/wpa_supplicant( 1385): Re-associate with C0.AA.48
I/wpa_supplicant( 1385): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1385): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/WifiMonitor( 1015): didn't find BSSID Trying to associate with SSID 'NG700'
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6179): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6179): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files,
,W/ResourcesManager( 6179): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6179): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6179): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/wpa_supplicant( 1385): Cmd 35605 not handled
,I/wpa_supplicant( 1385): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1385): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030,
I/wpa_supplicant( 1385): Associated with C0.AA.48
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false,
D/Tethering( 1015): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, true
D/Tethering( 1015): interfaceLinkStateChanged wlan0, true
D/Tethering( 1015): interfaceStatusChanged wlan0, true
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
E/Tethering( 1015): No numeric data
D/Tethering( 1015): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1015): clearTetheredNotification()
,V/NetworkStats( 1015): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/HotspotTile( 1176): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1176): updateTetherState():false, false
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,V/NetworkStats( 1015): performPollLocked() took 4ms
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,W/ActivityThread( 6179): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6179): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e663115: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6179): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6179): GMSCore installation verified
,I/ConfigStore( 6179): Config Database version: 1
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1015): getStreamVolume 3 index 70
,I/MediaRouter( 6179): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,V/MusicLeanback( 6179): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6207): MountEmulatedStorage(),
,E/Zygote  ( 6207): v2
,I/libpersona( 6207): KNOX_SDCARD checking this for 10001
I/libpersona( 6207): KNOX_SDCARD not a persona
,I/SELinux ( 6207): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6207 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6207): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6207): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/GHttpClientFactory( 6179): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6207): TimaSignature is unavailable
,D/ActivityThread( 6207): Added TimaKeyStore provider
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 6179): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1015): Killing 5613:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6226): MountEmulatedStorage(),
E/Zygote  ( 6226): v2
I/libpersona( 6226): KNOX_SDCARD checking this for 1000
I/libpersona( 6226): KNOX_SDCARD not a persona
,I/SELinux ( 6226): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6226 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 4190:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/SELinux ( 6226): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6226): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6226): TimaSignature is unavailable
,D/ActivityThread( 6226): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 6226): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1015): failed to open /acct/uid_10139/pid_5613/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10032/pid_4190/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6226): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6226): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6226): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6226): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6226): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6226): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6241): MountEmulatedStorage(),
E/Zygote  ( 6241): v2
,I/libpersona( 6241): KNOX_SDCARD checking this for 10008
I/libpersona( 6241): KNOX_SDCARD not a persona,
,I/SELinux ( 6241): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1015): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6241 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1015): Killing 5183:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,I/SELinux ( 6241): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6241): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6241): TimaSignature is unavailable
,D/ActivityThread( 6241): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 8709(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 619us total 28.772ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 17.013ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 16.516ms
,I/ActivityManager( 1015): Killing 5265:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3604): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 05 01:40:26 GMT+01:00 2016
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3604): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3604): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3604): KLMSSystemProperties(): getBoolean(): ro.product_ship = true,
,I/KLMS-2.5.123: ( 3604): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.123: ( 3604): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.123: ( 3604): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,W/libprocessgroup( 1015): failed to open /acct/uid_10032/pid_5183/cgroup.procs: No such file or directory
E/Zygote  ( 6257): MountEmulatedStorage()
E/Zygote  ( 6257): v2
I/libpersona( 6257): KNOX_SDCARD checking this for 10031
I/libpersona( 6257): KNOX_SDCARD not a persona
,I/SELinux ( 6257): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6257): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6257): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3604): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/ActivityManager( 1015): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6257 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3604): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3604): KLMSIntentService(): onDestroy(),
,D/TimaKeyStoreProvider( 6257): TimaSignature is unavailable
,D/ActivityThread( 6257): Added TimaKeyStore provider
,I/SO_AGENT( 6257): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,W/libprocessgroup( 1015): failed to open /acct/uid_10014/pid_5265/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5712): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5712): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
I/SA      ( 5766): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5766): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 5766): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5712): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5712): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5712): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 5766): [SLFUCHKMGR] constructor called
,I/SA      ( 5766): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5766): [OR] == isSIMCardReady false ==
,I/SA      ( 5766): [SCU] == networkStateCheck == false
,I/SA      ( 5766): [OR] onReceive END
,I/ActivityManager( 1015): Killing 5658:com.samsung.helphub/1000 (adj 15): empty #31
,V/DownloadManager( 1219): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1585): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1636): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1585): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1585): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1585): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1585): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1585): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1585): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6274): MountEmulatedStorage()
,E/Zygote  ( 6274): v2
I/libpersona( 6274): KNOX_SDCARD checking this for 10121
I/libpersona( 6274): KNOX_SDCARD not a persona
,I/SELinux ( 6274): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6274 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,I/SELinux ( 6274): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6274): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6274): TimaSignature is unavailable
,D/ActivityThread( 6274): Added TimaKeyStore provider
,W/ResourcesManager( 6274): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6274): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6274): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6274): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6274): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6274): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6289): MountEmulatedStorage()
,E/Zygote  ( 6289): v2
I/libpersona( 6289): KNOX_SDCARD checking this for 10141
I/libpersona( 6289): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6289 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,I/SELinux ( 6289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Killing 5697:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,I/SELinux ( 6289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6289): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6289): TimaSignature is unavailable
,D/ActivityThread( 6289): Added TimaKeyStore provider
,W/ResourcesManager( 6289): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6289): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6289): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6289): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5658/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10087/pid_5697/cgroup.procs: No such file or directory
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/BadgeProvider( 5811): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/BadgeProvider( 5811): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5811): sendNotify, [notify] : null
D/BadgeProvider( 5811): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5811): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5811): update, [UpdateCount] : 1
,D/Launcher.Model( 1479): reloadBadges entered.
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6312): MountEmulatedStorage(),
I/libpersona( 6312): KNOX_SDCARD checking this for 1000,
E/Zygote  ( 6312): v2
I/libpersona( 6312): KNOX_SDCARD not a persona
,I/SELinux ( 6312): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6312 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6312): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6312): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6312): TimaSignature is unavailable
,D/ActivityThread( 6312): Added TimaKeyStore provider
,D/SecurityLogAgent( 6312): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6312): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6312): StateMachine : Current State = 1
,D/SecurityLogAgent( 6312): StateMachine : Changed Current State = 1
,I/ActivityManager( 1015): Killing 5281:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/iu.Environment( 2077): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2077): num queued entries: 0
,I/iu.UploadsManager( 2077): num updated entries: 0
,I/iu.SyncManager( 2077): NEXT; no task
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 50888(2MB) AllocSpace objects, 9(196KB) LOS objects, 33% free, 23MB/35MB, paused 2.871ms total 178.091ms
,W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ChimeraCfgMgr( 2077): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/Babel   ( 4022): connection state changed from CONNECTED to DISCONNECTED
,E/Zygote  ( 6332): MountEmulatedStorage()
E/Zygote  ( 6332): v2
I/libpersona( 6332): KNOX_SDCARD checking this for 10032
I/libpersona( 6332): KNOX_SDCARD not a persona
,I/SELinux ( 6332): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6332): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1015): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6332 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6332): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 5750:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6332): TimaSignature is unavailable
,D/ActivityThread( 6332): Added TimaKeyStore provider
,W/libprocessgroup( 1015): failed to open /acct/uid_10029/pid_5281/cgroup.procs: No such file or directory
,E/SPPClientService( 6332): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6332): [PushClientApplication] Push log off : This is Ship build version
E/SPPClientService( 6332): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6332): [SystemStateMoniter] Current Time : 162697
,E/SPPClientService( 6332): [SystemStateMoniter] No Connect : true
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6332): PushLog.txt file is not deleted.,
D/SPPClientService( 6332): PushLog.txt file is not deleted.
D/SPPClientService( 6332): ============PushLog. stop!
,E/Zygote  ( 6349): MountEmulatedStorage()
E/Zygote  ( 6349): v2
I/libpersona( 6349): KNOX_SDCARD checking this for 10110
I/libpersona( 6349): KNOX_SDCARD not a persona
,I/SELinux ( 6349): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6349 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 5787:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
I/SELinux ( 6349): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6349): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SPPClientService( 6332): [[SystemStateMonitorService]] No Active Internet
,W/libprocessgroup( 1015): failed to open /acct/uid_10148/pid_5750/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6349): TimaSignature is unavailable
,D/ActivityThread( 6349): Added TimaKeyStore provider
,W/libprocessgroup( 1015): failed to open /acct/uid_10152/pid_5787/cgroup.procs: No such file or directory
,I/GAv4    ( 6349): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6349):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6349):   adb logcat -s GAv4
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6349): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6349): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6349): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6349): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 6349): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6349): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6349): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6349): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6349): Time to load native libraries: 2 ms (timestamps 3145-3147)
,I/LibraryLoader( 6349): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6349): Binding Chromium to main looper Looper (main, tid 1) {1df0572}
,I/LibraryLoader( 6349): Expected native library version number "",actual native library version number ""
,I/chromium( 6349): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6349): Initializing chromium process, singleProcess=true
,W/art     ( 6349): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6349): ApplicationContext is null in ApplicationStatus
,W/chromium( 6349): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6349): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6349): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6349): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6349): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6349): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6349): Local Branch: 
I/Adreno-EGL( 6349): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6349): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6349):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 6349): Requires BLUETOOTH permission
,I/NSApplication( 6349): Starting up...
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6405): MountEmulatedStorage()
,E/Zygote  ( 6405): v2
I/libpersona( 6405): KNOX_SDCARD checking this for 10077
I/libpersona( 6405): KNOX_SDCARD not a persona
,I/SELinux ( 6405): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1015): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6405 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1015): Killing 5649:com.android.mms/u0a41 (adj 15): empty #31
,I/SELinux ( 6405): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6405): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6405): TimaSignature is unavailable
,D/ActivityThread( 6405): Added TimaKeyStore provider
,D/CountryDetector( 1015): No listener is left
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,W/libprocessgroup( 1015): failed to open /acct/uid_10041/pid_5649/cgroup.procs: No such file or directory
,E/SMD     (  289): DCD OFF
,I/ActivityManager( 1015): Killing 5821:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10042/pid_5821/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1385): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1385): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1385): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,I/wpa_supplicant( 1385): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48,
I/wpa_supplicant( 1385): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1385): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,I/wpa_supplicant( 1385): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1385): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1385): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 1385): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1385): Blacklist: Clear (temp) 
,I/wpa_supplicant( 1385): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, true
D/Tethering( 1015): interfaceStatusChanged wlan0, true
,D/WifiNative-wlan0( 1015): callSECApiVoid - ID [50]
,E/WifiConfigStore( 1015): setLastSelectedConfiguration -1
,D/ConnectivityService( 1015): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1015): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1682): Starting #10
I/Hs20UtilService( 1682): Message received 5007
,D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1308): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
,I/NearbySettings( 1308): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1308): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1308): MountReceiver.mPrefHandler - 7002
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  279): Setting iface cfg
,E/WifiStateMachine( 1015): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1015): mCursor = null
,E/WifiNative-wlan0( 1015): do suspend false
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,E/dhcpcd  ( 6426): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 6426): version 5.5.6 starting,
,E/dhcpcd  ( 6426): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 6426): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 6426): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6426): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6426): bssid match
,I/dhcpcd  ( 6426): wlan0: rebinding lease of 192.168.1.132,
,I/dhcpcd  ( 6426): wlan0: acknowledged 192.168.1.132 from 192.168.1.1,
,I/dhcpcd  ( 6426): wlan0: leased 192.168.1.132 for 86400 seconds,
,E/WifiNative-wlan0( 1015): do suspend true,
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1015): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK,
E/WifiStateMachine( 1015): VerifyingLinkState enter
D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiNative-wlan0( 1015): callSECApiInt - ID [210]
,E/ConnectivityService( 1015): updateNetworkInfo()
,D/ConnectivityService( 1015): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1015): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1015): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1015): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check,
D/ConnectivityService( 1015): Adding Route [fe80::/64 -> :: wlan0] to network 503
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/ConnectivityService( 1015): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,I/Hs20UtilService( 1682): Starting #11
,I/Hs20UtilService( 1682): Message received 5007
,D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1308): MountReceiver.onReceive - Keep current state
,D/ConnectivityService( 1015): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1015): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1015): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1015): LTETest block dns file not exists
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 1015): updateNetworkInfo()
,E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1015): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Connected
D/ConnectivityService( 1015): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 1000
I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
,D/ConnectivityService( 1015):    accepting network in place of null,
D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1444): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1444): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker( 1015): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1015): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1015): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/Tethering( 1015): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1015): MasterInitialState.processMessage what=3
,D/ConnectivityService( 1015): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
I/Hs20UtilService( 1682): Starting #12
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524290
,V/NetworkStats( 1015): updateIfacesLocked()
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---,
,D/StatusBar.NetworkController( 1176): EthernetConnected: false
V/NetworkStats( 1015): performPollLocked() took 5ms
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
I/WifiTrafficPoller( 1015): mBoosterFLAG : 0
I/WifiTrafficPoller( 1015): current booster mode : FullMode
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/Hs20UtilService( 1682): Message received 5007
D/WifiNative-wlan0( 1015): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1308): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1308): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
I/NearbySettings( 1308): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1308): MountReceiver.onReceive - Keep current state
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6103): BLE supported!!
I/jxcore-log( 6103): 
,I/Hs20UtilService( 1682): Starting #13
,I/Hs20UtilService( 1682): Message received 5007
,D/WifiStateMachine( 1015): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityYOffset
I/System.out( 1015): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1015): mCursor = null
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1015): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,D/SRIB_DCS( 1176): log_dcs ThreadedRenderer::initialize entered! 
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 00:40:29 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1451954429682], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1451954429665]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Validated
,D/ConnectivityService( 1015): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1015): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1015): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1015): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1176): EthernetConnected: false
,D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 5682): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5682): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5682): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5682): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1015): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1015): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1015): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,I/NetworkMonitor( 6179): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,V/MusicLeanback( 6179): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/DIAGMON_AGENT( 6226): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6226): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6226): ./extraInfo: "NG700"
I/DIAGMON_AGENT( 6226): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1015): mCursor = null
,I/DBG_POLICYDM( 5712): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5712): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5712): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5712): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO,
,I/DBG_POLICYDM( 5712): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5712): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6241): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6241): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 3604): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 05 01:40:30 GMT+01:00 2016
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3604): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3604): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3604): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3604): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3604): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3604): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3604): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3604): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3604): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.5.123: ( 3604): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3604): StateImplV2(): networkChangeListener().END
,I/DBG_POLICYDM( 5712): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3604): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 5712): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5712): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5712): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 5766): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5766): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5766): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5766): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5766): [OR] == isSIMCardReady false ==
,I/SA      ( 5766): [SCU] == networkStateCheck == true
,I/SA      ( 5766): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5766): isChinaCountryCode : false
I/SA      ( 5766): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5766): [OR] == networkStateCheck true ==
,I/DBG_POLICYDM( 5712): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 5766): [OR] GetMyCountryZoneTask
I/SA      ( 5766): [OR] onReceive END,
,V/DownloadManager( 1219): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 5712): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,D/accuweather( 1585): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5766): [SRS] prepareGetMyCountryZone
I/DBG_POLICYDM( 5712): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5712): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5712): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5712): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,D/daemonapp( 1636): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,I/DBG_POLICYDM( 5712): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5712): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5712): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,D/SecContentProvider2( 1015): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1015): mCursor = null
,I/SA      ( 5766): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5766): [SSP] query invoked
D/accuweather( 1585): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1585): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1585): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1585): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5712): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,I/SA      ( 5766): [TPMU] GetMccFromDB : null
I/SA      ( 5766): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5766): [TPM] isNoProxy(default) : true
,D/accuweather( 1585): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1585): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/QuickConnect( 6274): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6274): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6274): PeriphStartReceiver.onReceive - no need to start
E/DBG_POLICYDM( 5712): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,E/File    ( 5766): fail readDirectory() errno=2
,I/DBG_POLICYDM( 5712): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5712): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/SecurityLogAgent( 6312): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6312): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6312): StateMachine : Current State = 1
,D/SecurityLogAgent( 6312): StateMachine : Changed Current State = 1
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,I/iu.Environment( 2077): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2077): num queued entries: 0
,I/iu.UploadsManager( 2077): num updated entries: 0
,I/iu.SyncManager( 2077): NEXT; no task
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2077): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2077): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/System.out( 4022): (HTTPLog)-Static: isSBSettingEnabled false
,E/SPPClientService( 6332): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6332): [SystemStateMoniter] Current Time : 166094
I/System.out( 4022): (HTTPLog)-Static: isSBSettingEnabled false
,E/SPPClientService( 6332): [SystemStateMoniter] No Connect : false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10102
,D/ConnectivityService( 1015): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 4022): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/WaitQueueForNetworkActivate( 5996): notifyNetworkActivated
,I/GLSUser ( 1768): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1768): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1768): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1768): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1768): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 4022): connection state changed from DISCONNECTED to CONNECTED
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ContextImpl( 5996): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1015): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
,W/Kids    ( 2077): [AccountUtils] Account not ready
W/Kids    ( 2077): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2077): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2077): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2077): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2077): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2077): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2077): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2077): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2077): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2077): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2077): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2077): 	at java.lang.Thread.run(Thread.java:818)
I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
,D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/GCM     ( 1768): Connected
,D/GCM     ( 1768): Message class com.google.f.a.a.p
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
D/hcjo    ( 5996): AutoUpdateManager:IDLE:execute
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/InitializeManagerStateMachine( 5996): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5996): exit::IDLE
D/InitializeManagerStateMachine( 5996): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5996): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5996): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5996): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5996): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5996): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5996): entry::SUCCESS
D/hcjo    ( 5996): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5996): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5996): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5996): exit::SUCCESS
,D/InitializeManagerStateMachine( 5996): entry::IDLE
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/SMD     (  289): DCD OFF
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SA      ( 5766): [RC New] Execute method=[GET] start
,I/MusicLeanback( 6179): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6179): Stop autocaching.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SA      ( 5766): [RC New] Security=[true]
,I/System.out( 5766): Thread-970(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5766): Thread-970(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5766): Thread-970(ApacheHTTPLog):isShipBuild true
I/System.out( 5766): Thread-970(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5766): Thread-970(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10036
,D/WearableService( 3709): callingUid 10011, callindPid: 3709
,E/GmsUtils( 6179): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6179): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,I/SA      ( 5766): [RC New] [v2liruge] api execute + 633
,I/SA      ( 5766): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5766): AsyncTask #1 calls detatch(),
,I/SA      ( 5766): [ODM] saveOpenData( GEO_IP, PL ),
,I/SA      ( 5766): [OCP] update openData : PL
,I/SA      ( 5766): [TPMU] getNetworkMcc : 
,I/SA      ( 5766): [SCU] saveMccToPreferece Start
,I/SA      ( 5766): [SCU] RegionMCC : 260
,I/SA      ( 5766): [SSP] query invoked
,I/SA      ( 5766): [TPMU] GetMccFromDB : null
,I/SA      ( 5766): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5766): [SCU] saveMccToPreferece End
,I/SA      ( 5766): [RC New] executeRequest [v2liruge] end. 697
I/SA      ( 5766): [RC New] Execute end
,I/SA      ( 5766): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5766): [OR] GetMyCountryZoneTask Success
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/Watchdog( 1015): !@Sync 5
,I/SurfaceFlinger(  258): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  258): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1015): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1015) eventTime = 168708
,D/PowerManagerService( 1015): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015 (0x0)
,D/PowerManagerService( 1015): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1015, ws=WorkSource{10049}) (elapsedTime=3485)
,I/dhcpcd  ( 6426): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6426): wlan0: sendmsg: Cannot assign requested address
,V/AlarmManager( 1015): waitForAlarm result :4
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,V/GLSActivity( 1768): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1768): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1768): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1768): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1768): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1768): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5352): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5352): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5352): [1] 5.onFinished: Scheduling replication attempt 5.,
,E/SMD     (  289): DCD OFF
,D/ConnectivityService( 1015): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524295
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524295
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5682): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5682): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5682): [GetString-S]
,I/ReactiveServiceManager( 5682): Supported : 1
,D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1015): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1015): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1015): handleString: Failed to handle string(-4)
E/terrier ( 1015): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5682): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5682): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5682): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5682): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5682): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5682): [ensureRegistration] - No Samsung account
,E/SMD     (  289): DCD OFF
,I/dhcpcd  ( 6426): wlan0: sending IPv6 Router Solicitation
,V/AlarmManager( 1015): waitForAlarm result :4
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1768): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1768): Vacuum at: now=1451954437426 tag=VacuumService
,I/GoogleURLConnFactory( 1768): Using platform SSLCertificateSocketFactory
,W/Uploader( 1768): No account for auth token provided
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 47377(2MB) AllocSpace objects, 6(100KB) LOS objects, 33% free, 23MB/35MB, paused 2.466ms total 155.652ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1768): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1768): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1768): (HTTPLog)-Static: isShipBuild true
I/System.out( 1768): (HTTPLog)-Thread-211-386469419: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1768): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,I/System.out( 1768): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1768): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1768, getuid(): 10011
,I/qtaguid ( 1768): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1768, getuid(): 10011
,W/Uploader( 1768): No account for auth token provided
,I/System.out( 1768): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1768): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1768, getuid(): 10011
,W/Uploader( 1768): No account for auth token provided
,I/System.out( 1768): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1768): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1768, getuid(): 10011
,W/Uploader( 1768):  no longer exists, so no auth token.
,I/System.out( 1768): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1768): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1768, getuid(): 10011
,W/Uploader( 1768): No account for auth token provided
,I/System.out( 1768): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1768): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1768, getuid(): 10011
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1768): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1768): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1768): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1768): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1768): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
,I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
E/Uploader( 1768): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1768): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1768): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1768): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1768): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1768): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1768): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1768): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1768): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1768): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1768): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1768): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1768): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1768): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1768): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1768, getuid(): 10011
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1768): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  289): DCD OFF
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps,
,D/PreloadUpdateManagerStateMachine( 5996): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5996): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5996): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5996): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5996): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 5996): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5996): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5996): entry::IDLE
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,I/dhcpcd  ( 6426): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6426): wlan0: no IPv6 Routers available
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 105s ago
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1015): waitForAlarm result :4
,V/GLSActivity( 1768): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1768): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1768): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1768): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1768): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1768): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5352): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5352): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5352): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/Watchdog( 1015): !@Sync 6
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false,
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 ,	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 140s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/Watchdog( 1015): !@Sync 7
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1015): [PWL] Off : 180s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/Watchdog( 1015): !@Sync 8
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6025): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6025): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1768): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1768): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1768): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1768): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1768): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1768): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1768): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1768): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1768): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1768): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6025): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6025): Soft error
E/BooksSync( 6025): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6025): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6025): Sync error
E/BooksSync( 6025): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6025): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6025): Finished books sync
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 284126, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/Watchdog( 1015): !@Sync 9
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 225s ago
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,V/AlarmManager( 1015): waitForAlarm result :8
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1015): initializing...
,I/TLC_TIMA_PKM_initialize( 1015): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1015): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1015): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1015): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1015): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1015): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1015): Trustlet response is completed
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/Watchdog( 1015): !@Sync 10
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate,
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/jxcore-log( 6103): Connected to the server!
I/jxcore-log( 6103): 
,I/chromium( 6103): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6025): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6025): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1768): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1768): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1768): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1768): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1768): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1768): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1768): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1768): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1768): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1768): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6025): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6025): Soft error
E/BooksSync( 6025): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6025): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6025): Sync error
E/BooksSync( 6025): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6025): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6025): Finished books sync
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 317382, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/Watchdog( 1015): !@Sync 11
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1015): [PWL] Off : 275s ago
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF
,V/GLSActivity( 1768): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1768): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1768): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1768): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1768): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1768): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found,
,W/GLSActivity( 1768): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1768): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1768): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1768): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1768): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1768): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1768): 	at android.os.Binder.execTransact(Binder.java:461)
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/PlayEventLogger( 5352): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5352): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5352): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5352): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5352): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5352): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5352): 	at android.os.Binder.execTransact(Binder.java:461)
D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
,I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/System  ( 5352): Ignoring header User-Agent because its value was null.
,I/System.out( 5352): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5352): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5352): (HTTPLog)-Static: isShipBuild true
I/System.out( 5352): (HTTPLog)-Thread-903-416294679: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 5352): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10026
,I/System.out( 5352): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1015): stay LED for fully charged
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/Watchdog( 1015): !@Sync 12
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 330s ago
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/Watchdog( 1015): !@Sync 13
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/BooksSync( 6025): Starting books sync for 61035162, extras: ade
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 6025): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1768): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1768): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1768): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1768): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1768): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
,I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1768): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1768): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1768): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1768): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1768): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6025): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6025): Soft error
E/BooksSync( 6025): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6025): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6025): Sync error
E/BooksSync( 6025): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6025): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6025): Finished books sync
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 410394, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1015): mCursor = null
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1015): !@Sync 14,
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/jxcore-log( 6103): --- start :testFindPeers.js---
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): testFindPeers created [object Object]
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): serverPort is 8876
I/jxcore-log( 6103): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): start: Peer ID: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT818
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6103): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6103): initialize: My bluetooth address is 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6103): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6103): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6103): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
D/BluetoothSocket( 6103): bindListen(), new LocalSocket 
D/BluetoothSocket( 6103): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6103): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2bbc23d4
D/BluetoothSocket( 6103): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): start: OK
I/io.jxcore.node.ConnectionHelper( 6103): start: Using peer discovery mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): start: Peer ID: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT818
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6103): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6103): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): start: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6103): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1015): InactiveState{ what=139292 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 1015): P2pEnabledState add service
,D/WifiP2pService( 1015): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): setState: INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6103): start: OK
,I/jxcore-log( 6103): StartBroadcasting started ok
I/jxcore-log( 6103): 
I/chromium( 6103): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6103): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onWifiStateChanged: State changed to 2
I/io.jxcore.node.ConnectionHelper( 6103): onDiscoveryManagerStateChanged: RUNNING
,D/WifiP2pService( 1015): InactiveState{ what=139265 },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6103): Local service added successfully
D/WifiP2pService( 1015): P2pEnabledState{ what=139265 }
,D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true,
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiP2pService( 1015): discovery change broadcast true
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1385): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2437,
D/WifiP2pService( 1015): InactiveState{ what=147477 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiDisplayController( 1015): Received list of peers.
,D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService( 1015): InactiveState{ what=139301 },
D/WifiP2pService( 1015): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1015): P2pEnabledState add service request
,D/WifiP2pManager( 6103): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service request added successfully
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/WifiP2pService( 1015): InactiveState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1015): P2pEnabledState discover services,
D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true,
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1385): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service discovery started successfully
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiDisplayController( 1015): Received list of peers.
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1015): InactiveState{ what=147494 },
D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9383","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
I/io.jxcore.node.ConnectionHelper( 6103): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
D/io.jxcore.node.ConnectionHelper( 6103): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383] is available
I/jxcore-log( 6103): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"LGE-Nexus 5_PT9383","peerAvailable":true}]
I/jxcore-log( 6103): 
I/jxcore-log( 6103): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 6103): 
I/jxcore-log( 6103): weAreDoneNow
I/jxcore-log( 6103): 
I/jxcore-log( 6103): done, now sending data to server
I/jxcore-log( 6103): 
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 390s ago
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/Watchdog( 1015): !@Sync 15
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/bootchecker(  313): bootchecker wake up!!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): setState: RESTARTING
,D/WifiP2pService( 1015): InactiveState{ what=139268 }
,I/wpa_supplicant( 1385): P2P-FIND-STOPPED 
,D/WifiP2pService( 1015): InactiveState{ what=147493 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1015): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): Start timer timeout, starting now...
,D/WifiP2pService( 1015): InactiveState{ what=139265 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139265 }
,D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1385): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1015): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started,
,E/Watchdog( 1015): !@Sync 16,
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): restart: Restarting...
,D/WifiP2pService( 1015): InactiveState{ what=139307 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1015): P2pEnabledState clear service request
,D/WifiP2pService( 1015): InactiveState{ what=139301 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1015): P2pEnabledState add service request
D/WifiP2pManager( 6103): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service request added successfully
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
,D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 },
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383],
,D/WifiP2pService( 1015): InactiveState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState discover services
,D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1385): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service discovery started successfully,
,E/SMD     (  289): DCD OFF
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 1385): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 6 device(s) discovered
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c,
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1015): Received list of peers.
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
,D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 6 device(s) discovered
,D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 6 device(s) discovered
D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
,D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 },
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
,D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged,
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/Watchdog( 1015): !@Sync 17
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): setState: RESTARTING
,D/WifiP2pService( 1015): InactiveState{ what=139268 }
,I/wpa_supplicant( 1385): P2P-FIND-STOPPED 
,D/WifiP2pService( 1015): InactiveState{ what=147493 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1015): discovery change broadcast false,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 455s ago,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): Start timer timeout, starting now...
,D/WifiP2pService( 1015): InactiveState{ what=139265 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139265 }
,D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1385): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): P2P device discovery started successfully,
D/WifiP2pService( 1015): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,E/SMD     (  289): DCD OFF
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437,
I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 },
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 7 device(s) discovered
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): restart: Restarting...
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/Wif,iP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 7 device(s) discovered
D/WifiP2pService( 1015): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1015): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1015): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/WifiP2pService( 1015): InactiveState{ what=139301 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1015): P2pEnabledState add service request
D/WifiP2pManager( 6103): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service request added successfully
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/WifiP2pService( 1015): InactiveState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState discover services
,D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1385): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1385): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service discovery started successfully
,I/wpa_supplicant( 1385): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1385): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1015): InactiveState{ what=147477 },
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 8 device(s) discovered
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 8 device(s) discovered
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/WifiP2pService( 1015): InactiveState{ what=147494 },
D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/io.jxcore.node.ConnectionHelper( 6103): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28,
D/io.jxcore.node.ConnectionHelper( 6103): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] is available
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1015): P2pEnabledState receive service response
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/io.jxcore.node.ConnectionHelper( 6103): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
,D/io.jxcore.node.ConnectionHelper( 6103): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] is available
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiDisplayController( 1015): Received list of peers.
,D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6025): Starting books sync for 61035162, extras: ade
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 67009(5MB) AllocSpace objects, 158(2MB) LOS objects, 33% free, 24MB/36MB, paused 2.446ms total 175.284ms
,I/BooksConfig( 6025): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1768): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1768): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1768): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1768): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1768): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1768): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1768): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1768): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1768): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1768): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6025): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6025): Soft error
E/BooksSync( 6025): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6025): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6025): Sync error
E/BooksSync( 6025): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6025): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6025): Finished books sync
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 542394, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,E/SMD     (  289): DCD OFF,
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1015): InactiveState{ what=147477 },
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): restart: Restarting...
,D/WifiP2pService( 1015): InactiveState{ what=139307 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1015): P2pEnabledState clear service request
,D/WifiP2pService( 1015): InactiveState{ what=139301 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1015): P2pEnabledState add service request
D/WifiP2pManager( 6103): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service request added successfully
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/WifiP2pService( 1015): InactiveState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState discover services
,D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1385): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service discovery started successfully
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437,
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/io.jxcore.node.ConnectionHelper( 6103): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6103): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/WifiP2pService( 1015): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
I/io.jxcore.node.ConnectionHelper( 6103): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
,D/io.jxcore.node.ConnectionHelper( 6103): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357] is available
,E/SMD     (  289): DCD OFF
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT177","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
,I/io.jxcore.node.ConnectionHelper( 6103): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 6103): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177] is available
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiP2pService( 1015): InactiveState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,E/SMD     (  289): DCD OFF,
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1015): InactiveState{ what=147477 },
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 },
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListCh,anged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 1015): !@Sync 18
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 7E.18.23 p2p_dev_addr=7E.18.23 pri_dev_type=10-0050F204-5  ' A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 },
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d,
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8,
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1015): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/WifiDisplayController( 1015): Received list of peers.
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): restart: Restarting...
,D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
,D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1015): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b,
D/WifiP2pService( 1015): P2pEnabledState{ what=139307 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true,
D/WifiP2pService( 1015): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383],
,D/WifiP2pService( 1015): InactiveState{ what=139301 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1015): P2pEnabledState add service request
D/WifiP2pManager( 6103): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service request added successfully
,D/WifiP2pService( 1015): InactiveState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState discover services
,D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1385): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service discovery started successfully
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
I/wpa_supplicant( 1385): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
,D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07,
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1015): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
I/io.jxcore.node.ConnectionHelper( 6103): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
,D/io.jxcore.node.ConnectionHelper( 6103): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706] is available
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1015): stay LED for fully charged
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,I/jxcore-log( 6103): teardown
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): testFindPeers stopped
I/jxcore-log( 6103): 
,I/io.jxcore.node.ConnectionHelper( 6103): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): shutdown
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@2a1a940, channel: 6, state: LISTENING
,D/BluetoothSocket( 6103): close() this: android.bluetooth.BluetoothSocket@2a1a940, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2bbc23d4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@7e6c079mSocket: android.net.LocalSocket@27b01be impl:android.net.LocalSocketImpl@1fdbd21f fd:FileDescriptor[109],
D/BluetoothSocket( 6103): Closing mSocket: android.net.LocalSocket@27b01be impl:android.net.LocalSocketImpl@1fdbd21f fd:FileDescriptor[109]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6103): release: No more listeners, de-initializing...
,D/WifiP2pService( 1015): InactiveState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): setState: NOT_STARTED
D/WifiP2pService( 1015): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): stop: Stopping peer discovery...
D/WifiP2pService( 1015): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): stop: Stopping services,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6103): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6103): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6103): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): setState: NOT_STARTED
I/jxcore-log( 6103): StopBroadcasting went ok
I/jxcore-log( 6103): 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Exiting thread,
D/WifiP2pService( 1015): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): onServerStopped
I/chromium( 6103): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6103): onConnectionManagerStateChanged: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 6103): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6103): Local services cleared successfully
I/wpa_supplicant( 1385): P2P-FIND-STOPPED 
,D/WifiP2pService( 1015): InactiveState{ what=139307 }
,I/jxcore-log( 6103): --- start :testSendData.js---
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 0
I/jxcore-log( 6103): 
,D/WifiP2pService( 1015): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1015): P2pEnabledState clear service request
D/WifiP2pService( 1015): remove channel information from framework
,D/WifiP2pService( 1015): InactiveState{ what=147493 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1015): discovery change broadcast false
,I/jxcore-log( 6103): daya100000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): check server
I/jxcore-log( 6103): 
I/jxcore-log( 6103): serverPort is 43634,
I/jxcore-log( 6103): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): start: Peer ID: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT818
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6103): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6103): initialize: My bluetooth address is 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6103): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6103): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6103): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[110]}
,D/BluetoothSocket( 6103): bindListen(), new LocalSocket 
D/BluetoothSocket( 6103): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6103): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1709eb35
D/BluetoothSocket( 6103): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): start: OK
I/io.jxcore.node.ConnectionHelper( 6103): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): start: Peer ID: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT818
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6103): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6103): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): start: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6103): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT818","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1015): InactiveState{ what=139292 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139292 }
D/WifiP2pService( 1015): P2pEnabledState add service
D/WifiP2pService( 1015): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6103): start: OK
,I/jxcore-log( 6103): StartBroadcasting started ok
I/jxcore-log( 6103): 
,D/WifiP2pService( 1015): InactiveState{ what=139265 }
D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiP2pService( 1015): P2pEnabledState{ what=139265 }
,D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1385): USE_NETWORK : USE_NETWORK OFF
,I/jxcore-log( 6103): null
I/jxcore-log( 6103): 
,D/WifiP2pService( 1015): discovery change broadcast true
,I/jxcore-log( 6103): 2016-01-05T00:47:23.587Z SendDataTCPServer.js: TCP/IP server is bound to port: 43634
I/jxcore-log( 6103): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service requests cleared successfully
I/chromium( 6103): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 6103): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onWifiStateChanged: State changed to 2
I/io.jxcore.node.ConnectionHelper( 6103): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6103): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/WifiP2pService( 1015): InactiveState{ what=139268 }
I/wpa_supplicant( 1385): P2P-FIND-STOPPED 
,D/WifiP2pService( 1015): InactiveState{ what=147493 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): P2P device discovery stopped successfully
D/WifiP2pService( 1015): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1015): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): setState: RESTARTING
,D/WifiP2pService( 1015): InactiveState{ what=139268 }
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/Atfwd_Daemon(  316): Stop the daemon....
,E/SMD     (  289): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): Start timer timeout, starting now...
,D/WifiP2pService( 1015): InactiveState{ what=139265 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139265 }
D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1385): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1015): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,E/SMD     (  289): DCD OFF,
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2437
I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 7E.18.23 p2p_dev_addr=7E.18.23 pri_dev_type=10-0050F204-5  ' A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1015): InactiveState{ what=147477 },
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
,D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo ,: null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac,
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pManager( 6103): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service request added successfully
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): InactiveState{ what=139301 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1015): P2pEnabledState add service request
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1015): InactiveState{ what=147477 },
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1015): InactiveState{ what=147477 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147477 },
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1015): InactiveState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState discover services
,D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1385): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1385): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service discovery started successfully
,I/wpa_supplicant( 1385): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1385): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,E/Watchdog( 1015): !@Sync 19,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4505","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1015): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
D/WifiP2pService( 1015): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
I/io.jxcore.node.ConnectionHelper( 6103): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
D/io.jxcore.node.ConnectionHelper( 6103): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505] is available
I/jxcore-log( 6103): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"motorola-XT1072_PT4505","peerAvailable":true}]
I/jxcore-log( 6103): 
I/jxcore-log( 6103): Found peer : motorola-XT1072_PT4505, Available: true
I/jxcore-log( 6103): 
I/jxcore-log( 6103): startWithNextDevice
I/jxcore-log( 6103): 
I/jxcore-log( 6103): device[1]: 44:80:EB:7B:5A:05
I/jxcore-log( 6103): 
I/jxcore-log( 6103): 2016-01-05T00:47:33.019Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
,I/jxcore-log( 6103): 
I/jxcore-log( 6103): 2016-01-05T00:47:33.019Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 6103): 
I/jxcore-log( 6103): 2016-01-05T00:47:33.019Z SendDataConnector.js: do connect now
I/jxcore-log( 6103): 
I/io.jxcore.node.ConnectionHelper( 6103): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 6103): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): connect: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): onConnecting: null 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): connect: Started connecting to null in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 6103): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 1055)
,D/BluetoothUtils( 6103): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 6103): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2639): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 2639): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 2639): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 2639): db_query_execute: result 1
,D/BluetoothSocket( 6103): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/IOP_DB_BT( 2639): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2639): db_query_execute: result 1
W/bt-btif ( 2639): info:x10
,D/        ( 2639): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2639): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.NAME_CHANGED
,W/bt-sdp  ( 2639): process_service_search_attr_rsp
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 2639): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
,D/SecContentProvider( 1015): uri = 4 selection = bluetoothLogForRemote
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.CLASS_CHANGED
,E/bt-btif ( 2639): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2639): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BtConfig.SecureMode( 2639): isSecureModeOn:false
,I/BluetoothBondStateMachine( 2639): Entering PendingCommandState State
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1176):  onBluetoothPairedDevicesChanged:
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1176):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1308): onReceive
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5926): BTStateChangeCB is registed
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5926): BluetoothHeadset service is binded
D/GMFPReceiver( 5926): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5926): jangil::setProperties()
,D/GMFPReceiver( 5926): jangil::printBTStatus()
,D/SettingsProvider( 1015): name = Wearable0001
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10098
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10098
,D/GMFPReceiver( 5926): ::::::::Wearable0001::false
,D/SettingsProvider( 1015): name = Wearable0002
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10098
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10098
,D/GMFPReceiver( 5926): ::::::::Wearable0002::false
,D/GMFPReceiver( 5926): onServiceConnected() : 1
D/GMFPReceiver( 5926): mBluetoothHeadset = true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,D/btif_config_util( 2639): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2639): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2639): Failed to remove device: 44:80:EB:7B:5A:05
,D/SecContentProvider( 1015): uri = 4 selection = bluetoothLogForRemote
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 2639): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2639): isSecureModeOn:false
D/BluetoothTile( 1176):  onBluetoothPairedDevicesChanged:
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1176):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1308): onReceive
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5926): BTStateChangeCB is registed
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,D/HidService( 2639): getHidService(): returning com.android.bluetooth.hid.HidService@348090d4
,D/SettingsProvider( 1015): name = bluetooth_input_device_priority_44:80:EB:7B:5A:05
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
D/HidService( 2639): Saved priority 44:80:EB:7B:5A:05 = -1
E/BluetoothHeadset( 5926): BluetoothHeadset service is binded
D/GMFPReceiver( 5926): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5926): jangil::setProperties()
D/SettingsProvider( 1015): name = bluetooth_a2dp_sink_priority_44:80:EB:7B:5A:05
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
D/SettingsProvider( 1015): name = bluetooth_headset_priority_44:80:EB:7B:5A:05
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,I/BluetoothBondStateMachine( 2639): StableState(): Entering Off State
D/GMFPReceiver( 5926): jangil::printBTStatus()
,D/SettingsProvider( 1015): name = Wearable0001
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
,D/SettingsProvider( 1015): selectionArgs: 10098
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/GMFPReceiver( 5926): ::::::::Wearable0001::false
D/SettingsProvider( 1015): name = Wearable0002
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10098
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/GMFPReceiver( 5926): ::::::::Wearable0002::false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
D/GMFPReceiver( 5926): onServiceConnected() : 1
D/GMFPReceiver( 5926): mBluetoothHeadset = true
,W/bt-btif ( 2639): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2639): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2639): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2639): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): onSocketConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1055)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): onBytesWritten: 82 bytes successfully written (thread ID: 1056)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Outgoing connection initialized (*handshake* thread ID: 1056)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Exiting thread (thread ID: 1055)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6103): Entering thread (ID: 1056)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): onBytesRead: Read 81 bytes successfully (thread ID: 1056)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): onHandshakeSucceeded: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6103): Exiting thread (ID: 1056)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
I/io.jxcore.node.ConnectionHelper( 6103): onConnected: Outgoing connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
D/io.jxcore.node.ConnectionHelper( 6103): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
,W/io.jxcore.node.ConnectionHelper( 6103): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6103): onConnected: Outgoing socket thread, for peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6103): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6103): Entering thread (ID: 1057)
,D/io.jxcore.node.OutgoingSocketThread( 6103): Server socket local port: 47073
,I/io.jxcore.node.OutgoingSocketThread( 6103): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 6103): onListeningForIncomingConnections: Outgoing connection is using port 47073 (peer ID: 44:80:EB:7B:5A:05)
,I/jxcore-log( 6103): 2016-01-05T00:47:35.118Z SendDataConnector.js: CLIENT connected to 47073, error: null
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:35.119Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6103): 
,I/io.jxcore.node.OutgoingSocketThread( 6103): Incoming data from address: /127.0.0.1, port: 47073
,D/io.jxcore.node.OutgoingSocketThread( 6103): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6103): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6103): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 6103): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread( 6103): Exiting thread (ID: 1057)
,D/io.jxcore.node.StreamCopyingThread( 6103): Entering thread (ID: 1059, name: Receiver),
,D/io.jxcore.node.StreamCopyingThread( 6103): Entering thread (ID: 1058, name: Sender)
,I/jxcore-log( 6103): 2016-01-05T00:47:35.135Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6103): 
,D/        ( 2639): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 6103): 2016-01-05T00:47:35.662Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:35.685Z SendDataConnector.js: CLIENT is data received : 20000,
I/jxcore-log( 6103): 
,D/        ( 2639): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 6103): 2016-01-05T00:47:35.725Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:35.813Z SendDataConnector.js: CLIENT is data received : 40000,
I/jxcore-log( 6103): 
,D/        ( 2639): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1936
,I/jxcore-log( 6103): 2016-01-05T00:47:35.853Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:35.925Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:35.928Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:35.932Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:35.994Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:35.999Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:36.000Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): oneRoundDownNow
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:36.003Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:36.004Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6103): 
,D/io.jxcore.node.ConnectionHelper( 6103): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
,I/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 44:80:EB:7B:5A:05
,I/io.jxcore.node.OutgoingSocketThread( 6103): close
D/io.jxcore.node.OutgoingSocketThread( 6103): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 6103): doStop: Thread ID: 1059
D/io.jxcore.node.OutgoingSocketThread( 6103): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6103): doStop: Thread ID: 1058
,D/io.jxcore.node.OutgoingSocketThread( 6103): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6103): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6103): Either failed to read from the output stream or write to the input stream (thread ID: 1058, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 6103): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6103): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6103): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 6103): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6103): closeBluetoothSocketAndStreams
,D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@12a36058, channel: 5, state: CONNECTED
D/BluetoothSocket( 6103): close() this: android.bluetooth.BluetoothSocket@12a36058, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12fb05b1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@28838a96mSocket: android.net.LocalSocket@1a3fe617 impl:android.net.LocalSocketImpl@321a2a04 fd:FileDescriptor[111]
,D/BluetoothSocket( 6103): Closing mSocket: android.net.LocalSocket@1a3fe617 impl:android.net.LocalSocketImpl@321a2a04 fd:FileDescriptor[111]
,W/io.jxcore.node.StreamCopyingThread( 6103): Either failed to read from the output stream or write to the input stream (thread ID: 1059, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 6103): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6103): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1,
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@12a36058, channel: 5, state: CLOSED
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@12a36058, channel: 5, state: CLOSED
,D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6103): disconnectOutgoingConnection: Successfully disconnected (peer ID: 44:80:EB:7B:5A:05
I/jxcore-log( 6103): 2016-01-05T00:47:36.020Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): ---- round done--------
I/jxcore-log( 6103): 
E/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6103): Exiting thread (ID: 1059, name: Receiver)
I/jxcore-log( 6103): startWithNextDevice
I/jxcore-log( 6103): 
E/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6103): Exiting thread (ID: 1058, name: Sender)
,W/bt-btif ( 2639): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,E/SMD     (  289): DCD OFF
,E/bt-btm  ( 2639): Reset sec_bd_name and name flag. (BR/EDR link),
E/bt-btm  ( 2639): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1176): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1308): ACTION_ACL_DISCONNECTED,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/KeyguardViewMediator( 1176): isGear1: device is not B1!
,D/BluetoothAdapterService( 2639): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1a56b2
,D/BtConfig.SecureMode( 2639): isSecureModeOn:false
,D/SecContentProvider( 1015): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2639): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5980): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,E/SMD     (  289): DCD OFF
,I/BluetoothClassifier( 5980): Bluetooth Device Name: XT1072
,D/IOP_DB_BT( 2639): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2639): db_query_execute: result 1
,D/IOP_DB_BT( 2639): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
,D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 2639): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2639): db_query_execute: result 1
,W/bt-btif ( 2639): info:x10
,D/        ( 2639): remote version info [7c:f9:0e:51:18:22]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2639): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.NAME_CHANGED
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/BluetoothBondStateMachine( 2639): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
,D/SecContentProvider( 1015): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2639): check_cod: remote_cod = 0x5a020c
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.NAME_CHANGED
V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.CLASS_CHANGED
,I/BluetoothBondStateMachine( 2639): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2639): isSecureModeOn:false
I/BluetoothBondStateMachine( 2639): Entering PendingCommandState State
,D/BluetoothTile( 1176):  onBluetoothPairedDevicesChanged:
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1176):  handleUpdatestate:false name:null
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 1308): onReceive
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5926): BTStateChangeCB is registed
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5926): BluetoothHeadset service is binded
,D/GMFPReceiver( 5926): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5926): jangil::setProperties()
,D/GMFPReceiver( 5926): jangil::printBTStatus()
,D/SettingsProvider( 1015): name = Wearable0001
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1015): selectionArgs: false
,D/SettingsProvider( 1015): selectionArgs: 10098
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1015): ret = -1
,D/GMFPReceiver( 5926): ::::::::Wearable0001::false
,D/SettingsProvider( 1015): name = Wearable0002
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
,D/SettingsProvider( 1015): selectionArgs: 10098
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1015): ret = -1
,D/GMFPReceiver( 5926): ::::::::Wearable0002::false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
D/GMFPReceiver( 5926): onServiceConnected() : 1
D/GMFPReceiver( 5926): mBluetoothHeadset = true
,D/btif_config_util( 2639): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2639): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2639): Failed to remove device: 7C:F9:0E:51:18:22
,D/SecContentProvider( 1015): uri = 4 selection = bluetoothLogForRemote
,D/BluetoothTile( 1176):  onBluetoothPairedDevicesChanged:
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,I/BluetoothBondStateMachine( 2639): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 2639): isSecureModeOn:false
V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/HidService( 2639): getHidService(): returning com.android.bluetooth.hid.HidService@348090d4
,D/SettingsProvider( 1015): name = bluetooth_input_device_priority_7C:F9:0E:51:18:22
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/BluetoothNotiBroadcastReceiver( 1308): onReceive
,D/BluetoothTile( 1176):  handleUpdatestate:false name:null
D/HidService( 2639): Saved priority 7C:F9:0E:51:18:22 = -1
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,D/SettingsProvider( 1015): name = bluetooth_a2dp_sink_priority_7C:F9:0E:51:18:22
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
E/BluetoothHeadset( 5926): BTStateChangeCB is registed
,D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
,D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1015): ret = -1
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/SettingsProvider( 1015): name = bluetooth_headset_priority_7C:F9:0E:51:18:22
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,I/BluetoothBondStateMachine( 2639): StableState(): Entering Off State
,E/BluetoothHeadset( 5926): BluetoothHeadset service is binded
,D/GMFPReceiver( 5926): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5926): jangil::setProperties()
,D/GMFPReceiver( 5926): jangil::printBTStatus()
,D/SettingsProvider( 1015): name = Wearable0001
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10098
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/GMFPReceiver( 5926): ::::::::Wearable0001::false
,D/SettingsProvider( 1015): name = Wearable0002
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10098
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/GMFPReceiver( 5926): ::::::::Wearable0002::false
D/GMFPReceiver( 5926): onServiceConnected() : 1
D/GMFPReceiver( 5926): mBluetoothHeadset = true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,W/bt-btif ( 2639): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2639): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2639): bta_dm_pm_ssr:2, lat:1200
,D/BluetoothSocket( 6103): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@11094bed
,E/BluetoothRemoteDevices( 2639): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Incoming connection initialized (thread ID: 1060)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6103): Entering thread (ID: 1060)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): onBytesRead: Read 83 bytes successfully (thread ID: 1060)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): onBytesWritten: 82 bytes successfully written (thread ID: 1060)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): removeThreadFromList: Removing thread with ID 1060
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Handshake thread disposed (thread ID: 1060)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6103): Exiting thread (ID: 1060)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,I/io.jxcore.node.ConnectionHelper( 6103): onConnected: Incoming connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/io.jxcore.node.ConnectionHelper( 6103): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper( 6103): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] is available
,I/jxcore-log( 6103): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT3690","peerAvailable":true}]
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): Found peer : samsung-SM-A500FU_PT3690, Available: true
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): startWithNextDevice
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): device[2]: 7C:F9:0E:51:18:22
I/jxcore-log( 6103): 
I/jxcore-log( 6103): 2016-01-05T00:47:41.404Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:41.404Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:41.404Z SendDataConnector.js: do connect now
I/jxcore-log( 6103): 
,I/io.jxcore.node.ConnectionHelper( 6103): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper( 6103): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): connect: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 6103): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 1061)
,I/io.jxcore.node.ConnectionHelper( 6103): onConnected: Incoming socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], created successfully
,D/io.jxcore.node.ConnectionHelper( 6103): onConnected: The total number of connections is now 1
,D/BluetoothUtils( 6103): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 6103): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2639): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 6103): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,D/io.jxcore.node.IncomingSocketThread( 6103): Entering thread (ID: 1062)
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10338
,I/io.jxcore.node.IncomingSocketThread( 6103): Local host address: localhost/127.0.0.1, port: 43634
,D/io.jxcore.node.IncomingSocketThread( 6103): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6103): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6103): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6103): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6103): Exiting thread (ID: 1062)
,I/jxcore-log( 6103): 2016-01-05T00:47:41.427Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6103): 
,D/io.jxcore.node.StreamCopyingThread( 6103): Entering thread (ID: 1064, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6103): Entering thread (ID: 1063, name: Sender)
,W/bt-sdp  ( 2639): process_service_search_attr_rsp
,W/bt-btif ( 2639): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2639): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2639): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2639): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2639): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): onSocketConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1061)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): onBytesWritten: 82 bytes successfully written (thread ID: 1065)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Outgoing connection initialized (*handshake* thread ID: 1065)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Exiting thread (thread ID: 1061)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6103): Entering thread (ID: 1065)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): onBytesRead: Read 83 bytes successfully (thread ID: 1065)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): onHandshakeSucceeded: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6103): Exiting thread (ID: 1065)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,I/io.jxcore.node.ConnectionHelper( 6103): onConnected: Outgoing connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,D/io.jxcore.node.ConnectionHelper( 6103): hasConnection: We have an incoming connection with peer with ID 7C:F9:0E:51:18:22
,W/io.jxcore.node.ConnectionHelper( 6103): onConnected: Already connected with peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 6103): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6103): onConnected: Outgoing socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6103): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 6103): Entering thread (ID: 1066)
,D/io.jxcore.node.OutgoingSocketThread( 6103): Server socket local port: 42731
I/io.jxcore.node.OutgoingSocketThread( 6103): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 6103): onListeningForIncomingConnections: Outgoing connection is using port 42731 (peer ID: 7C:F9:0E:51:18:22)
,I/jxcore-log( 6103): 2016-01-05T00:47:41.796Z SendDataConnector.js: CLIENT connected to 42731, error: null
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:41.797Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:41.800Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6103): 
,I/io.jxcore.node.OutgoingSocketThread( 6103): Incoming data from address: /127.0.0.1, port: 42731
,D/io.jxcore.node.OutgoingSocketThread( 6103): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6103): setBufferSize: Setting buffer size to 8192 bytes,
I/io.jxcore.node.StreamCopyingThread( 6103): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6103): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6103): Exiting thread (ID: 1066)
,D/io.jxcore.node.StreamCopyingThread( 6103): Entering thread (ID: 1067, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6103): Entering thread (ID: 1068, name: Receiver)
,D/        ( 2639): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:3324
,I/jxcore-log( 6103): 2016-01-05T00:47:42.219Z SendDataTCPServer.js: TCP/IP server has received 20240 bytes of data,
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.262Z SendDataTCPServer.js: TCP/IP server has received 22264 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.300Z SendDataTCPServer.js: TCP/IP server has received 26312 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.303Z SendDataTCPServer.js: TCP/IP server has received 28336 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.311Z SendDataTCPServer.js: TCP/IP server has received 30360 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.325Z SendDataTCPServer.js: TCP/IP server has received 32384 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.328Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.360Z SendDataTCPServer.js: TCP/IP server has received 36432 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.402Z SendDataTCPServer.js: TCP/IP server has received 38456 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.428Z SendDataTCPServer.js: TCP/IP server has received 40480 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.434Z SendDataTCPServer.js: TCP/IP server has received 42504 bytes of data
I/jxcore-log( 6103): 
,D/        ( 2639): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:18628
,I/jxcore-log( 6103): 2016-01-05T00:47:42.466Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.468Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.472Z SendDataTCPServer.js: TCP/IP server has received 50600 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.476Z SendDataTCPServer.js: TCP/IP server has received 52624 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.483Z SendDataTCPServer.js: TCP/IP server has received 54648 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.519Z SendDataTCPServer.js: TCP/IP server has received 60720 bytes of data
I/jxcore-log( 6103): 
,D/        ( 2639): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:8508
,I/jxcore-log( 6103): 2016-01-05T00:47:42.555Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.592Z SendDataTCPServer.js: TCP/IP server has received 62744 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.629Z SendDataTCPServer.js: TCP/IP server has received 72864 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.642Z SendDataTCPServer.js: TCP/IP server has received 74888 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.665Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.679Z SendDataTCPServer.js: TCP/IP server has received 80960 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.711Z SendDataTCPServer.js: TCP/IP server has received 82984 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.750Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.756Z SendDataTCPServer.js: TCP/IP server has received 93104 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.759Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.790Z SendDataTCPServer.js: TCP/IP server has received 99176 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.797Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.802Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.811Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.859Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6103): 
,W/bt-btif ( 2639): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 6103): Either failed to read from the output stream or write to the input stream (thread ID: 1064, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 6103): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 6103): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1062
,D/io.jxcore.node.OutgoingSocketThread( 6103): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6103): doStop: Thread ID: 1064
,D/io.jxcore.node.OutgoingSocketThread( 6103): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6103): doStop: Thread ID: 1063
,D/io.jxcore.node.OutgoingSocketThread( 6103): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6103): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6103): Either failed to read from the output stream or write to the input stream (thread ID: 1063, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 6103): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6103): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6103): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6103): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 6103): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@3c65ba22, channel: 6, state: CONNECTED
D/BluetoothSocket( 6103): close() this: android.bluetooth.BluetoothSocket@3c65ba22, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e52ccb3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1911e270mSocket: android.net.LocalSocket@323bb9e9 impl:android.net.LocalSocketImpl@949566e fd:FileDescriptor[109]
I/jxcore-log( 6103): 2016-01-05T00:47:42.893Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6103): 
D/BluetoothSocket( 6103): Closing mSocket: android.net.LocalSocket@323bb9e9 impl:android.net.LocalSocketImpl@949566e fd:FileDescriptor[109]
,D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@3c65ba22, channel: 6, state: CLOSED
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@3c65ba22, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6103): Exiting thread (ID: 1064, name: Receiver)
D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6103): Exiting thread (ID: 1063, name: Sender)
,I/jxcore-log( 6103): 2016-01-05T00:47:42.922Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.923Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): oneRoundDownNow
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.925Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:47:42.925Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6103): 
,D/io.jxcore.node.ConnectionHelper( 6103): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
,I/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
,I/io.jxcore.node.OutgoingSocketThread( 6103): close
D/io.jxcore.node.OutgoingSocketThread( 6103): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 6103): doStop: Thread ID: 1068
D/io.jxcore.node.OutgoingSocketThread( 6103): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 6103): doStop: Thread ID: 1067
D/io.jxcore.node.OutgoingSocketThread( 6103): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 6103): closeLocalSocketAndStreams: Closing the local input stream...
,D/io.jxcore.node.OutgoingSocketThread( 6103): closeLocalSocketAndStreams: Closing the local output stream...
,W/io.jxcore.node.StreamCopyingThread( 6103): Either failed to read from the output stream or write to the input stream (thread ID: 1067, thread name: Sender): Socket closed,
E/io.jxcore.node.OutgoingSocketThread( 6103): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6103): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6103): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 6103): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@13a3810f, channel: 6, state: CONNECTED
,D/BluetoothSocket( 6103): close() this: android.bluetooth.BluetoothSocket@13a3810f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e8ab59c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@70d0ba5mSocket: android.net.LocalSocket@20b86b7a impl:android.net.LocalSocketImpl@39a11f2b fd:FileDescriptor[112]
,D/BluetoothSocket( 6103): Closing mSocket: android.net.LocalSocket@20b86b7a impl:android.net.LocalSocketImpl@39a11f2b fd:FileDescriptor[112]
W/io.jxcore.node.StreamCopyingThread( 6103): Either failed to read from the output stream or write to the input stream (thread ID: 1068, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 6103): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6103): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@13a3810f, channel: 6, state: CLOSED
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@13a3810f, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6103): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
E/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6103): Exiting thread (ID: 1068, name: Receiver)
I/jxcore-log( 6103): 2016-01-05T00:47:42.939Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6103): 
D/io.jxcore.node.StreamCopyingThread( 6103): Exiting thread (ID: 1067, name: Sender)
,I/jxcore-log( 6103): ---- round done--------
I/jxcore-log( 6103): 
I/jxcore-log( 6103): startWithNextDevice
I/jxcore-log( 6103): 
,E/SMD     (  289): DCD OFF
,W/bt-btif ( 2639): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/bt-btm  ( 2639): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2639): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1176): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1308): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2639): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1a56b2
,D/BtConfig.SecureMode( 2639): isSecureModeOn:false
,D/KeyguardViewMediator( 1176): isGear1: device is not B1!
,D/SecContentProvider( 1015): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2639): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5980): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5980): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/PowerManagerService( 1015): [PWL] Off : 525s ago
,I/PowerManagerService( 1015): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1015): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=2639, ws=null) (elapsedTime=4626)
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1015): waitForAlarm result :8,
,D/TimaService( 1015): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1015): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1015): TimaServiceHandler.handleMessage what =1
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1015): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1015): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): setState: RESTARTING
,D/WifiP2pService( 1015): InactiveState{ what=139268 }
,I/wpa_supplicant( 1385): P2P-FIND-STOPPED 
,D/WifiP2pService( 1015): InactiveState{ what=147493 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1015): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/Watchdog( 1015): !@Sync 20
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): Start timer timeout, starting now...
,D/WifiP2pService( 1015): InactiveState{ what=139265 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139265 }
D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1385): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1015): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437,
I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 7E.18.23 p2p_dev_addr=7E.18.23 pri_dev_type=10-0050F204-5  ' A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1015): InactiveState{ what=147477 },
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 },
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): DefaultState{ what=139283 },
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1015): InactiveState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505], add/update: true
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1015): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): restart: Restarting...
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 12 device(s) discovered
,D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07,
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505], add/update: true
D/WifiP2pService( 1015): P2pEnabledState{ what=139307 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
D/WifiP2pService( 1015): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1015): InactiveState{ what=139301 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1015): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pService( 1015): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 6103): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service request added successfully
,D/WifiP2pService( 1015): InactiveState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState discover services
,D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1385): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service discovery started successfully,
,E/SMD     (  289): DCD OFF
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437,
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
,D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505], add/update: true,
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
,D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505], add/update: true
D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9383","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
I/io.jxcore.node.ConnectionHelper( 6103): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 6103): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383] already in the list, will not add again
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/io.jxcore.node.ConnectionHelper( 6103): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6103): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] already in the list, will not add again
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3690","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
I/io.jxcore.node.ConnectionHelper( 6103): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6103): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] already in the list, will not add again
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT706","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
I/io.jxcore.node.ConnectionHelper( 6103): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6103): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706] already in the list, will not add again
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1015): InactiveState{ what=147477 },
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT706]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): ,onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/IOP_DB_BT( 2639): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2639): db_query_execute: result 1
,D/IOP_DB_BT( 2639): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2639): db_query_execute: result 1
W/bt-btif ( 2639): info:x10
D/        ( 2639): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
E/BluetoothRemoteDevices( 2639): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.NAME_CHANGED
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1015): InactiveState{ what=147477 },
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
,D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1779","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
I/io.jxcore.node.ConnectionHelper( 6103): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 6103): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] is available
I/jxcore-log( 6103): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT1779","peerAvailable":true}]
I/jxcore-log( 6103): 
I/jxcore-log( 6103): Found peer : LGE-LG-D722_PT1779, Available: true
I/jxcore-log( 6103): 
I/jxcore-log( 6103): startWithNextDevice
I/jxcore-log( 6103): 
I/jxcore-log( 6103): device[3]: F8:95:C7:87:85:54
I/jxcore-log( 6103): 
I/jxcore-log( 6103): 2016-01-05T00:48:12.452Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 6103): 
I/jxcore-log( 6103): 2016-01-05T00:48:12.452Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 6103): 
I/jxcore-log( 6103): 2016-01-05T00:48:12.452Z SendDataConnector.js: do connect now
I/jxcore-log( 6103): 
I/io.jxcore.node.ConnectionHelper( 6103): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 6103): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 6103): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 1069)
,D/BluetoothUtils( 6103): isSocketAllowedBySecurityPolicy start : device null,
W/BluetoothAdapter( 6103): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2639): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/BluetoothSocket( 6103): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
,D/IOP_DB_BT( 2639): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_VER, value 6:16653
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 2639): db_query_execute: result 1
E/bt-btm  ( 2639): tBTM_SEC_DEV:0xa46ae9b8 rs_disc_pending=1
W/bt-btif ( 2639): bta_dm_check_av:0
,W/bt-btif ( 2639): btif_dm_cback : unhandled event (14)
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/SMD     (  289): DCD OFF
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 },
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9197","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
I/io.jxcore.node.ConnectionHelper( 6103): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 6103): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197] is available
I/jxcore-log( 6103): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT9197","peerAvailable":true}]
I/jxcore-log( 6103): 
I/jxcore-log( 6103): Found peer : samsung-SM-A500FU_PT9197, Available: true
I/jxcore-log( 6103): 
,D/SSRM:n  ( 1015): SIOP:: AP = 260,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiDisplayController( 1015): Received list of peers.
,D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 13 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2437,
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], add/update: true
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/IOP_DB_BT( 2639): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54
,D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_VER, value 6:16653
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2639): db_query_execute: result 1
W/bt-btif ( 2639): info:x10
D/        ( 2639): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2639): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.NAME_CHANGED
,E/SMD     (  289): DCD OFF
,W/bt-sdp  ( 2639): process_service_search_attr_rsp
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 2639): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,D/SecContentProvider( 1015): uri = 4 selection = bluetoothLogForRemote
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.CLASS_CHANGED
,E/bt-btif ( 2639): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2639): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver onReceive
D/BtConfig.SecureMode( 2639): isSecureModeOn:false
I/BluetoothBondStateMachine( 2639): Entering PendingCommandState State
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1176):  onBluetoothPairedDevicesChanged:
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1176):  handleUpdatestate:false name:null,
,D/BluetoothNotiBroadcastReceiver( 1308): onReceive
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5926): BTStateChangeCB is registed
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5926): BluetoothHeadset service is binded,
D/GMFPReceiver( 5926): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5926): jangil::setProperties()
,D/GMFPReceiver( 5926): jangil::printBTStatus()
,D/SettingsProvider( 1015): name = Wearable0001
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10098
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/GMFPReceiver( 5926): ::::::::Wearable0001::false
,D/SettingsProvider( 1015): name = Wearable0002
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10098
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/GMFPReceiver( 5926): ::::::::Wearable0002::false
,D/GMFPReceiver( 5926): onServiceConnected() : 1
D/GMFPReceiver( 5926): mBluetoothHeadset = true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/btif_config_util( 2639): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2639): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2639): Failed to remove device: F8:95:C7:87:3C:51
,D/SecContentProvider( 1015): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2639): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver onReceive
D/BtConfig.SecureMode( 2639): isSecureModeOn:false
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1176):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/HidService( 2639): getHidService(): returning com.android.bluetooth.hid.HidService@348090d4
,D/BluetoothTile( 1176):  handleUpdatestate:false name:null
,D/SettingsProvider( 1015): name = bluetooth_input_device_priority_F8:95:C7:87:3C:51
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/HidService( 2639): Saved priority F8:95:C7:87:3C:51 = -1
,D/SettingsProvider( 1015): name = bluetooth_a2dp_sink_priority_F8:95:C7:87:3C:51
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/BluetoothNotiBroadcastReceiver( 1308): onReceive
,D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1015): ret = -1
,D/SettingsProvider( 1015): name = bluetooth_headset_priority_F8:95:C7:87:3C:51
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,I/BluetoothBondStateMachine( 2639): StableState(): Entering Off State
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5926): BTStateChangeCB is registed
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5926): BluetoothHeadset service is binded
,D/GMFPReceiver( 5926): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5926): jangil::setProperties()
,D/GMFPReceiver( 5926): jangil::printBTStatus()
,D/SettingsProvider( 1015): name = Wearable0001
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
,D/SettingsProvider( 1015): selectionArgs: 10098
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1015): ret = -1
,D/GMFPReceiver( 5926): ::::::::Wearable0001::false
,D/SettingsProvider( 1015): name = Wearable0002
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
,D/SettingsProvider( 1015): selectionArgs: 10098
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1015): ret = -1
,D/GMFPReceiver( 5926): ::::::::Wearable0002::false
,D/GMFPReceiver( 5926): onServiceConnected() : 1
,D/GMFPReceiver( 5926): mBluetoothHeadset = true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,W/bt-btif ( 2639): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2639): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2639): bta_dm_pm_ssr:2, lat:1200
,D/BluetoothSocket( 6103): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@275b8f88
,E/BluetoothRemoteDevices( 2639): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Incoming connection initialized (thread ID: 1070)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6103): Entering thread (ID: 1070)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): onBytesRead: Read 76 bytes successfully (thread ID: 1070)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): onBytesWritten: 82 bytes successfully written (thread ID: 1070)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): removeThreadFromList: Removing thread with ID 1070
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Handshake thread disposed (thread ID: 1070)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6103): Exiting thread (ID: 1070)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
I/io.jxcore.node.ConnectionHelper( 6103): onConnected: Incoming connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177]
D/io.jxcore.node.ConnectionHelper( 6103): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
,W/io.jxcore.node.ConnectionHelper( 6103): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6103): onConnected: Incoming socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177], created successfully
,D/io.jxcore.node.ConnectionHelper( 6103): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 6103): Entering thread (ID: 1071)
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10338
,I/io.jxcore.node.IncomingSocketThread( 6103): Local host address: localhost/127.0.0.1, port: 43634
,D/io.jxcore.node.IncomingSocketThread( 6103): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6103): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6103): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6103): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6103): Exiting thread (ID: 1071)
,D/io.jxcore.node.StreamCopyingThread( 6103): Entering thread (ID: 1072, name: Sender)
I/jxcore-log( 6103): 2016-01-05T00:48:17.925Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6103): 
,D/io.jxcore.node.StreamCopyingThread( 6103): Entering thread (ID: 1073, name: Receiver)
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 2639): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,D/SecContentProvider( 1015): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2639): check_cod: remote_cod = 0x5a020c
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.CLASS_CHANGED
,I/BluetoothBondStateMachine( 2639): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 2639): isSecureModeOn:false
I/BluetoothBondStateMachine( 2639): Entering PendingCommandState State
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1176):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1176):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1308): onReceive
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5926): BTStateChangeCB is registed
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5926): BluetoothHeadset service is binded
D/GMFPReceiver( 5926): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5926): jangil::setProperties()
,D/GMFPReceiver( 5926): jangil::printBTStatus()
,D/SettingsProvider( 1015): name = Wearable0001
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10098
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
D/GMFPReceiver( 5926): ::::::::Wearable0001::false
D/SettingsProvider( 1015): name = Wearable0002
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10098
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
D/GMFPReceiver( 5926): ::::::::Wearable0002::false
D/GMFPReceiver( 5926): onServiceConnected() : 1,
D/GMFPReceiver( 5926): mBluetoothHeadset = true
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/btif_config_util( 2639): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2639): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2639): Failed to remove device: F8:95:C7:87:85:54
,D/SecContentProvider( 1015): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2639): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10,
D/BtConfig.SecureMode( 2639): isSecureModeOn:false
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver onReceive,
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/BluetoothTile( 1176):  onBluetoothPairedDevicesChanged:
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11,
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
D/HidService( 2639): getHidService(): returning com.android.bluetooth.hid.HidService@348090d4
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1176):  handleUpdatestate:false name:null
D/SettingsProvider( 1015): name = bluetooth_input_device_priority_F8:95:C7:87:85:54
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/HidService( 2639): Saved priority F8:95:C7:87:85:54 = -1
,D/SettingsProvider( 1015): name = bluetooth_a2dp_sink_priority_F8:95:C7:87:85:54
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1015): ret = -1
,D/BluetoothNotiBroadcastReceiver( 1308): onReceive
,D/SettingsProvider( 1015): name = bluetooth_headset_priority_F8:95:C7:87:85:54
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,I/BluetoothBondStateMachine( 2639): StableState(): Entering Off State
,E/BluetoothHeadset( 5926): BTStateChangeCB is registed
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5926): BluetoothHeadset service is binded
D/GMFPReceiver( 5926): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5926): jangil::setProperties()
,D/GMFPReceiver( 5926): jangil::printBTStatus()
,D/SettingsProvider( 1015): name = Wearable0001
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10098
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
D/GMFPReceiver( 5926): ::::::::Wearable0001::false
,D/SettingsProvider( 1015): name = Wearable0002
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10098
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/GMFPReceiver( 5926): ::::::::Wearable0002::false
,D/GMFPReceiver( 5926): onServiceConnected() : 1
D/GMFPReceiver( 5926): mBluetoothHeadset = true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,W/bt-btif ( 2639): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2639): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2639): bta_dm_pm_ssr:2, lat:1200
E/BluetoothRemoteDevices( 2639): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): onSocketConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1069)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): onBytesWritten: 82 bytes successfully written (thread ID: 1074)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Outgoing connection initialized (*handshake* thread ID: 1074)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Exiting thread (thread ID: 1069)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6103): Entering thread (ID: 1074)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): onBytesRead: Read 77 bytes successfully (thread ID: 1074)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Handshake succeeded with [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): onHandshakeSucceeded: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6103): Exiting thread (ID: 1074)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
,I/io.jxcore.node.ConnectionHelper( 6103): onConnected: Outgoing connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/io.jxcore.node.ConnectionHelper( 6103): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 6103): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6103): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6103): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 6103): Entering thread (ID: 1075)
,D/io.jxcore.node.OutgoingSocketThread( 6103): Server socket local port: 42797
,I/io.jxcore.node.OutgoingSocketThread( 6103): Now accepting connections...
,W/bt-btif ( 2639): new conn_srvc id:26, app_id:255
,D/BluetoothSocket( 6103): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@32e7bd21
,W/bt-btif ( 2639): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2639): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2639): bta_dm_pm_ssr:2, lat:1200
E/BluetoothRemoteDevices( 2639): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Incoming connection initialized (thread ID: 1076)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6103): Entering thread (ID: 1076)
,I/jxcore-log( 6103): 2016-01-05T00:48:18.608Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:18.613Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:18.618Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:18.687Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:18.692Z SendDataTCPServer.js: TCP/IP server has received 10120 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:18.704Z SendDataTCPServer.js: TCP/IP server has received 12144 bytes of data
I/jxcore-log( 6103): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): onBytesRead: Read 77 bytes successfully (thread ID: 1076)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): onBytesWritten: 82 bytes successfully written (thread ID: 1076)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): removeThreadFromList: Removing thread with ID 1076
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Handshake thread disposed (thread ID: 1076)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6103): Exiting thread (ID: 1076)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
I/io.jxcore.node.ConnectionHelper( 6103): onConnected: Incoming connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779]
D/io.jxcore.node.ConnectionHelper( 6103): hasConnection: We have an outgoing connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 6103): onConnected: Already connected with peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 6103): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6103): onConnected: Incoming socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779], created successfully
,D/io.jxcore.node.ConnectionHelper( 6103): onConnected: The total number of connections is now 3
,D/io.jxcore.node.IncomingSocketThread( 6103): Entering thread (ID: 1077)
,I/io.jxcore.node.IncomingSocketThread( 6103): Local host address: localhost/127.0.0.1, port: 43634
,I/jxcore-log( 6103): 2016-01-05T00:48:18.723Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6103): 
,D/io.jxcore.node.IncomingSocketThread( 6103): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6103): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6103): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 6103): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 6103): Exiting thread (ID: 1077)
,I/jxcore-log( 6103): 2016-01-05T00:48:18.730Z SendDataTCPServer.js: TCP/IP server has received 22456 bytes of data
I/jxcore-log( 6103): 
,D/io.jxcore.node.StreamCopyingThread( 6103): Entering thread (ID: 1079, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6103): Entering thread (ID: 1078, name: Sender)
,I/jxcore-log( 6103): 2016-01-05T00:48:18.735Z SendDataTCPServer.js: TCP/IP server has received 24480 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:18.770Z SendDataTCPServer.js: TCP/IP server has received 40672 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:18.775Z SendDataTCPServer.js: TCP/IP server has received 42696 bytes of data
I/jxcore-log( 6103): 
,I/io.jxcore.node.ConnectionHelper( 6103): onListeningForIncomingConnections: Outgoing connection is using port 42797 (peer ID: F8:95:C7:87:85:54)
,I/jxcore-log( 6103): 2016-01-05T00:48:18.778Z SendDataConnector.js: CLIENT connected to 42797, error: null
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:18.780Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6103): 
,I/io.jxcore.node.IncomingSocketThread( 6103): Incoming data from address: /127.0.0.1, port: 42797
,D/io.jxcore.node.IncomingSocketThread( 6103): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6103): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6103): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 6103): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6103): Exiting thread (ID: 1075)
,D/io.jxcore.node.StreamCopyingThread( 6103): Entering thread (ID: 1081, name: Receiver)
,I/jxcore-log( 6103): 2016-01-05T00:48:18.792Z SendDataTCPServer.js: TCP/IP server has received 46744 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:18.793Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6103): 
,D/io.jxcore.node.StreamCopyingThread( 6103): Entering thread (ID: 1080, name: Sender)
,E/SMD     (  289): DCD OFF
,I/jxcore-log( 6103): 2016-01-05T00:48:19.216Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6103): 
,W/io.jxcore.node.StreamCopyingThread( 6103): Either failed to read from the output stream or write to the input stream (thread ID: 1073, thread name: Receiver): bt socket closed, read return: -1
,W/bt-btif ( 2639): invalid rfc slot id: 7
E/io.jxcore.node.IncomingSocketThread( 6103): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6103): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1071
D/io.jxcore.node.IncomingSocketThread( 6103): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 6103): doStop: Thread ID: 1073
D/io.jxcore.node.IncomingSocketThread( 6103): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6103): doStop: Thread ID: 1072
,D/io.jxcore.node.IncomingSocketThread( 6103): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6103): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6103): closeLocalSocketAndStreams: Closing the local output stream...
,W/io.jxcore.node.StreamCopyingThread( 6103): Either failed to read from the output stream or write to the input stream (thread ID: 1072, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6103): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6103): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT177] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 6103): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6103): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@30d1c546, channel: 6, state: CONNECTED
D/BluetoothSocket( 6103): close() this: android.bluetooth.BluetoothSocket@30d1c546, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@d908307, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2cde1c34mSocket: android.net.LocalSocket@b620a5d impl:android.net.LocalSocketImpl@18d4efd2 fd:FileDescriptor[109]
D/BluetoothSocket( 6103): Closing mSocket: android.net.LocalSocket@b620a5d impl:android.net.LocalSocketImpl@18d4efd2 fd:FileDescriptor[109]
I/jxcore-log( 6103): 2016-01-05T00:48:19.295Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6103): 
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@30d1c546, channel: 6, state: CLOSED
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@30d1c546, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6103): Exiting thread (ID: 1073, name: Receiver)
D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6103): Exiting thread (ID: 1072, name: Sender)
,W/bt-rfcomm( 2639): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0,
W/bt-rfcomm( 2639): RFCOMM_DisconnectInd LCID:0x48
,I/jxcore-log( 6103): 2016-01-05T00:48:19.597Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:19.603Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:19.608Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:19.613Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:19.619Z SendDataTCPServer.js: TCP/IP server has received 10120 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:19.651Z SendDataTCPServer.js: TCP/IP server has received 12144 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:19.689Z SendDataTCPServer.js: TCP/IP server has received 18216 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:19.704Z SendDataTCPServer.js: TCP/IP server has received 20240 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:19.755Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:19.796Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:19.856Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:19.965Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.076Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.132Z SendDataTCPServer.js: TCP/IP server has received 22264 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.169Z SendDataTCPServer.js: TCP/IP server has received 24288 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.238Z SendDataTCPServer.js: TCP/IP server has received 26312 bytes of data,
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.244Z SendDataTCPServer.js: TCP/IP server has received 28336 bytes of data,
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.249Z SendDataTCPServer.js: TCP/IP server has received 30360 bytes of data,
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.255Z SendDataTCPServer.js: TCP/IP server has received 32384 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.290Z SendDataTCPServer.js: TCP/IP server has received 34408 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.303Z SendDataTCPServer.js: TCP/IP server has received 36432 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.308Z SendDataTCPServer.js: TCP/IP server has received 38456 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.388Z SendDataTCPServer.js: TCP/IP server has received 40480 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.394Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.405Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.510Z SendDataTCPServer.js: TCP/IP server has received 42504 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.550Z SendDataTCPServer.js: TCP/IP server has received 44528 bytes of data,
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.559Z SendDataTCPServer.js: TCP/IP server has received 46552 bytes of data,
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.563Z SendDataTCPServer.js: TCP/IP server has received 48576 bytes of data,
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.568Z SendDataTCPServer.js: TCP/IP server has received 50600 bytes of data,
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.620Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.620Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6103): 
I/jxcore-log( 6103): oneRoundDownNow
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.621Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6103): 
I/jxcore-log( 6103): 2016-01-05T00:48:20.621Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6103): 
,D/io.jxcore.node.ConnectionHelper( 6103): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
I/io.jxcore.node.IncomingSocketThread( 6103): close
D/io.jxcore.node.IncomingSocketThread( 6103): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 6103): doStop: Thread ID: 1081
,D/io.jxcore.node.IncomingSocketThread( 6103): close: Stopping sending thread...,
I/io.jxcore.node.StreamCopyingThread( 6103): doStop: Thread ID: 1080
D/io.jxcore.node.IncomingSocketThread( 6103): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6103): closeLocalSocketAndStreams: Closing the local input stream...
,D/io.jxcore.node.IncomingSocketThread( 6103): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6103): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6103): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@22848a3, channel: 8, state: CONNECTED
D/BluetoothSocket( 6103): close() this: android.bluetooth.BluetoothSocket@22848a3, channel: 8, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25ac7a0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2f39ef59mSocket: android.net.LocalSocket@3a6e371e impl:android.net.LocalSocketImpl@34eccbff fd:FileDescriptor[111]
D/BluetoothSocket( 6103): Closing mSocket: android.net.LocalSocket@3a6e371e impl:android.net.LocalSocketImpl@34eccbff fd:FileDescriptor[111]
,W/io.jxcore.node.StreamCopyingThread( 6103): Either failed to read from the output stream or write to the input stream (thread ID: 1080, thread name: Sender): Socket closed,
W/io.jxcore.node.StreamCopyingThread( 6103): Either failed to read from the output stream or write to the input stream (thread ID: 1081, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6103): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
E/io.jxcore.node.IncomingSocketThread( 6103): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6103): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed,
W/io.jxcore.node.ConnectionHelper( 6103): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@22848a3, channel: 8, state: CLOSED
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@22848a3, channel: 8, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left,
I/io.jxcore.node.ConnectionHelper( 6103): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:85:54
E/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6103): Exiting thread (ID: 1080, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
,D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6103): Exiting thread (ID: 1081, name: Receiver)
,I/jxcore-log( 6103): 2016-01-05T00:48:20.628Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54,
I/jxcore-log( 6103): 
I/jxcore-log( 6103): ---- round done--------
I/jxcore-log( 6103): 
I/jxcore-log( 6103): startWithNextDevice
I/jxcore-log( 6103): 
I/jxcore-log( 6103): device[4]: 7C:F9:0E:37:96:AB
I/jxcore-log( 6103): 
I/jxcore-log( 6103): 2016-01-05T00:48:20.630Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6103): 
I/jxcore-log( 6103): 2016-01-05T00:48:20.630Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6103): 
I/jxcore-log( 6103): 2016-01-05T00:48:20.630Z SendDataConnector.js: do connect now
I/jxcore-log( 6103): 
I/io.jxcore.node.ConnectionHelper( 6103): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 6103): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): connect: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 6103): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/jxcore-log( 6103): 2016-01-05T00:48:20.642Z SendDataTCPServer.js: TCP/IP server has received 52624 bytes of data
I/jxcore-log( 6103): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 1082)
,D/BluetoothUtils( 6103): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 6103): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2639): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 2639): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 2639): db_query_execute: result 1
,D/BluetoothSocket( 6103): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
,I/jxcore-log( 6103): 2016-01-05T00:48:20.660Z SendDataTCPServer.js: TCP/IP server has received 54648 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.664Z SendDataTCPServer.js: TCP/IP server has received 56672 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.667Z SendDataTCPServer.js: TCP/IP server has received 58696 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:20.671Z SendDataTCPServer.js: TCP/IP server has received 60720 bytes of data
I/jxcore-log( 6103): 
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 6103): 2016-01-05T00:48:21.271Z SendDataTCPServer.js: TCP/IP server has received 62744 bytes of data
I/jxcore-log( 6103): 
,E/SMD     (  289): DCD OFF
,I/jxcore-log( 6103): 2016-01-05T00:48:22.271Z SendDataTCPServer.js: TCP/IP server has received 64768 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:22.276Z SendDataTCPServer.js: TCP/IP server has received 66792 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:22.281Z SendDataTCPServer.js: TCP/IP server has received 68816 bytes of data
I/jxcore-log( 6103): 
,D/IOP_DB_BT( 2639): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2639): db_query_execute: result 1
W/bt-btif ( 2639): info:x10
,D/        ( 2639): remote version info [7c:f9:0e:37:96:ab]: 0, 0, 0
,E/BluetoothRemoteDevices( 2639): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2639): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,I/jxcore-log( 6103): 2016-01-05T00:48:22.295Z SendDataTCPServer.js: TCP/IP server has received 70840 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:22.300Z SendDataTCPServer.js: TCP/IP server has received 72864 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:22.340Z SendDataTCPServer.js: TCP/IP server has received 85008 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:22.347Z SendDataTCPServer.js: TCP/IP server has received 87032 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:22.350Z SendDataTCPServer.js: TCP/IP server has received 89056 bytes of data
I/jxcore-log( 6103): 
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.NAME_CHANGED
,I/jxcore-log( 6103): 2016-01-05T00:48:22.359Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:22.389Z SendDataTCPServer.js: TCP/IP server has received 99176 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:22.415Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6103): 
,W/bt-sdp  ( 2639): process_service_search_attr_rsp
,W/bt-btif ( 2639): invalid rfc slot id: 10
,W/io.jxcore.node.StreamCopyingThread( 6103): Either failed to read from the output stream or write to the input stream (thread ID: 1079, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6103): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 6103): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1077
D/io.jxcore.node.IncomingSocketThread( 6103): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6103): doStop: Thread ID: 1079
,D/io.jxcore.node.IncomingSocketThread( 6103): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6103): doStop: Thread ID: 1078
,D/io.jxcore.node.IncomingSocketThread( 6103): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6103): closeLocalSocketAndStreams: Closing the local input stream...
,D/io.jxcore.node.IncomingSocketThread( 6103): closeLocalSocketAndStreams: Closing the local output stream...
W/io.jxcore.node.StreamCopyingThread( 6103): Either failed to read from the output stream or write to the input stream (thread ID: 1078, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6103): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6103): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1779] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 6103): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6103): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@3534bdcc, channel: 6, state: CONNECTED
,D/BluetoothSocket( 6103): close() this: android.bluetooth.BluetoothSocket@3534bdcc, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11112815, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@13c2a72amSocket: android.net.LocalSocket@2d4c291b impl:android.net.LocalSocketImpl@23d5eab8 fd:FileDescriptor[116]
D/BluetoothSocket( 6103): Closing mSocket: android.net.LocalSocket@2d4c291b impl:android.net.LocalSocketImpl@23d5eab8 fd:FileDescriptor[116]
,D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@3534bdcc, channel: 6, state: CLOSED
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@3534bdcc, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6103): Exiting thread (ID: 1079, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6103): Exiting thread (ID: 1078, name: Sender)
,I/jxcore-log( 6103): 2016-01-05T00:48:22.472Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6103): 
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.NAME_CHANGED
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.CLASS_CHANGED
I/BluetoothBondStateMachine( 2639): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,D/SecContentProvider( 1015): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2639): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
,D/BluetoothTile( 1176):  onBluetoothPairedDevicesChanged:
,D/BtConfig.SecureMode( 2639): isSecureModeOn:false
,D/BluetoothTile( 1176):  handleUpdatestate:false name:null
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
I/BluetoothBondStateMachine( 2639): Entering PendingCommandState State
E/bt-btif ( 2639): check_cod: remote_cod = 0x5a020c
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothNotiBroadcastReceiver( 1308): onReceive
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5926): BTStateChangeCB is registed
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5926): BluetoothHeadset service is binded
D/GMFPReceiver( 5926): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5926): jangil::setProperties()
,D/GMFPReceiver( 5926): jangil::printBTStatus()
,D/SettingsProvider( 1015): name = Wearable0001
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
,D/SettingsProvider( 1015): selectionArgs: 10098
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/GMFPReceiver( 5926): ::::::::Wearable0001::false
,D/SettingsProvider( 1015): name = Wearable0002
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10098
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/GMFPReceiver( 5926): ::::::::Wearable0002::false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/GMFPReceiver( 5926): onServiceConnected() : 1
D/GMFPReceiver( 5926): mBluetoothHeadset = true
,D/btif_config_util( 2639): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2639): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2639): Failed to remove device: 7C:F9:0E:37:96:AB
,D/SecContentProvider( 1015): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2639): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 2639): isSecureModeOn:false
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
D/HidService( 2639): getHidService(): returning com.android.bluetooth.hid.HidService@348090d4
V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/SettingsProvider( 1015): name = bluetooth_input_device_priority_7C:F9:0E:37:96:AB
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
D/HidService( 2639): Saved priority 7C:F9:0E:37:96:AB = -1
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,W/bt-btif ( 2639): new conn_srvc id:26, app_id:1
W/bt-btif ( 2639): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2639): bta_dm_pm_ssr:2, lat:1200
,D/BluetoothTile( 1176):  onBluetoothPairedDevicesChanged:
,E/BluetoothRemoteDevices( 2639): setRfcommConnected true
,D/SettingsProvider( 1015): name = bluetooth_a2dp_sink_priority_7C:F9:0E:37:96:AB
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/SettingsProvider( 1015): name = bluetooth_headset_priority_7C:F9:0E:37:96:AB
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
I/BluetoothBondStateMachine( 2639): StableState(): Entering Off State
,D/BluetoothTile( 1176):  handleUpdatestate:false name:null
D/BluetoothNotiBroadcastReceiver( 1308): onReceive
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5926): BTStateChangeCB is registed
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): onSocketConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1082)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5926): BluetoothHeadset service is binded
D/GMFPReceiver( 5926): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5926): jangil::setProperties()
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): onBytesWritten: 82 bytes successfully written (thread ID: 1083)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Outgoing connection initialized (*handshake* thread ID: 1083)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Exiting thread (thread ID: 1082)
,D/GMFPReceiver( 5926): jangil::printBTStatus()
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6103): Entering thread (ID: 1083)
,D/SettingsProvider( 1015): name = Wearable0001
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10098
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/GMFPReceiver( 5926): ::::::::Wearable0001::false
D/SettingsProvider( 1015): name = Wearable0002
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10098
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): onBytesRead: Read 83 bytes successfully (thread ID: 1083)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6103): Handshake succeeded with [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): onHandshakeSucceeded: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6103): Exiting thread (ID: 1083)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
I/io.jxcore.node.ConnectionHelper( 6103): onConnected: Outgoing connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
D/GMFPReceiver( 5926): ::::::::Wearable0002::false
D/io.jxcore.node.ConnectionHelper( 6103): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/GMFPReceiver( 5926): onServiceConnected() : 1
D/GMFPReceiver( 5926): mBluetoothHeadset = true
,W/io.jxcore.node.ConnectionHelper( 6103): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197] already in the list, will not add again
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,I/io.jxcore.node.ConnectionHelper( 6103): onConnected: Outgoing socket thread, for peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6103): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6103): Entering thread (ID: 1084),
D/io.jxcore.node.OutgoingSocketThread( 6103): Server socket local port: 32789
I/io.jxcore.node.OutgoingSocketThread( 6103): Now accepting connections...
,E/bt-btm  ( 2639): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2639): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1176): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1308): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/KeyguardViewMediator( 1176): isGear1: device is not B1!
,D/BluetoothAdapterService( 2639): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1a56b2
,D/BtConfig.SecureMode( 2639): isSecureModeOn:false
,D/SecContentProvider( 1015): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2639): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5980): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5980): Bluetooth Device Name: G4-1
,I/io.jxcore.node.ConnectionHelper( 6103): onListeningForIncomingConnections: Outgoing connection is using port 32789 (peer ID: 7C:F9:0E:37:96:AB)
,I/jxcore-log( 6103): 2016-01-05T00:48:23.141Z SendDataConnector.js: CLIENT connected to 32789, error: null
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:23.142Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:23.145Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6103): 
,I/io.jxcore.node.OutgoingSocketThread( 6103): Incoming data from address: /127.0.0.1, port: 32789
,D/io.jxcore.node.OutgoingSocketThread( 6103): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6103): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6103): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 6103): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6103): Exiting thread (ID: 1084)
,D/io.jxcore.node.StreamCopyingThread( 6103): Entering thread (ID: 1086, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6103): Entering thread (ID: 1085, name: Sender)
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/        ( 2639): PORT_WriteDataCO: tx queue is full,tx.queue_size:10216,tx.queue.count:11,available:25520
,I/jxcore-log( 6103): 2016-01-05T00:48:23.660Z SendDataConnector.js: CLIENT is data received : 10000,
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:23.741Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6103): 
,D/        ( 2639): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:14388
,I/jxcore-log( 6103): 2016-01-05T00:48:23.813Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:23.895Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6103): 
,D/        ( 2639): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:3256
I/jxcore-log( 6103): 2016-01-05T00:48:23.961Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:24.003Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6103): 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,I/jxcore-log( 6103): 2016-01-05T00:48:24.146Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:24.190Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:24.296Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:24.348Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:24.350Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6103): 
I/jxcore-log( 6103): oneRoundDownNow
I/jxcore-log( 6103): 
I/jxcore-log( 6103): 2016-01-05T00:48:24.350Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:24.351Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6103): 
,D/io.jxcore.node.ConnectionHelper( 6103): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.OutgoingSocketThread( 6103): close
D/io.jxcore.node.OutgoingSocketThread( 6103): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6103): doStop: Thread ID: 1086
D/io.jxcore.node.OutgoingSocketThread( 6103): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6103): doStop: Thread ID: 1085
D/io.jxcore.node.OutgoingSocketThread( 6103): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6103): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 6103): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6103): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6103): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@31e93091, channel: 6, state: CONNECTED
D/BluetoothSocket( 6103): close() this: android.bluetooth.BluetoothSocket@31e93091, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e3c0bf6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@317a3bf7mSocket: android.net.LocalSocket@275afa64 impl:android.net.LocalSocketImpl@75f44cd fd:FileDescriptor[111]
D/BluetoothSocket( 6103): Closing mSocket: android.net.LocalSocket@275afa64 impl:android.net.LocalSocketImpl@75f44cd fd:FileDescriptor[111]
W/io.jxcore.node.StreamCopyingThread( 6103): Either failed to read from the output stream or write to the input stream (thread ID: 1086, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6103): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6103): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@31e93091, channel: 6, state: CLOSED
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@31e93091, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.StreamCopyingThread( 6103): Either failed to read from the output stream or write to the input stream (thread ID: 1085, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6103): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6103): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.ConnectionHelper( 6103): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
I/jxcore-log( 6103): 2016-01-05T00:48:24.356Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6103): 
,D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/jxcore-log( 6103): ---- round done--------
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): startWithNextDevice
I/jxcore-log( 6103): 
W/bt-btif ( 2639): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
E/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB,
D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6103): Exiting thread (ID: 1085, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 6103): Exiting thread (ID: 1086, name: Receiver)
,E/SMD     (  289): DCD OFF
,E/bt-btm  ( 2639): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2639): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1176): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1308): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/KeyguardViewMediator( 1176): isGear1: device is not B1!
,D/BluetoothAdapterService( 2639): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1a56b2
,D/BtConfig.SecureMode( 2639): isSecureModeOn:false
,D/SecContentProvider( 1015): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2639): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5980): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5980): Bluetooth Device Name: G3s-1
,E/SMD     (  289): DCD OFF
,D/IOP_DB_BT( 2639): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2639): db_query_execute: result 1
,E/bt-btm  ( 2639): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2639): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1176): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.ACL_DISCONNECTED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
E/BluetoothEventManager( 1308): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 1176): isGear1: device is not B1!
D/BluetoothAdapterService( 2639): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1a56b2
D/BtConfig.SecureMode( 2639): isSecureModeOn:false
,D/SecContentProvider( 1015): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2639): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5980): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5980): Bluetooth Device Name: A5-1
,D/IOP_DB_BT( 2639): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 2639): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2639): db_query_execute: result 1
W/bt-btif ( 2639): info:x10
D/        ( 2639): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2639): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.NAME_CHANGED
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.NAME_CHANGED
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.CLASS_CHANGED
,I/BluetoothBondStateMachine( 2639): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
,D/SecContentProvider( 1015): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2639): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2639): isSecureModeOn:false
I/BluetoothBondStateMachine( 2639): Entering PendingCommandState State
E/bt-btif ( 2639): check_cod: remote_cod = 0x5a020c
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1176):  onBluetoothPairedDevicesChanged:,
V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1176):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1308): onReceive
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5926): BTStateChangeCB is registed
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5926): BluetoothHeadset service is binded
D/GMFPReceiver( 5926): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5926): jangil::setProperties()
,D/GMFPReceiver( 5926): jangil::printBTStatus()
,D/SettingsProvider( 1015): name = Wearable0001
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10098
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
D/GMFPReceiver( 5926): ::::::::Wearable0001::false
D/SettingsProvider( 1015): name = Wearable0002
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10098
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/GMFPReceiver( 5926): ::::::::Wearable0002::false
D/GMFPReceiver( 5926): onServiceConnected() : 1
D/GMFPReceiver( 5926): mBluetoothHeadset = true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/btif_config_util( 2639): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2639): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2639): Failed to remove device: 58:3F:54:73:64:C0
,D/SecContentProvider( 1015): uri = 4 selection = bluetoothLogForRemote
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
I/BluetoothBondStateMachine( 2639): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2639): isSecureModeOn:false
,D/BluetoothTile( 1176):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/HidService( 2639): getHidService(): returning com.android.bluetooth.hid.HidService@348090d4
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1176):  handleUpdatestate:false name:null
,D/SettingsProvider( 1015): name = bluetooth_input_device_priority_58:3F:54:73:64:C0
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/HidService( 2639): Saved priority 58:3F:54:73:64:C0 = -1
,D/SettingsProvider( 1015): name = bluetooth_a2dp_sink_priority_58:3F:54:73:64:C0
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/SettingsProvider( 1015): name = bluetooth_headset_priority_58:3F:54:73:64:C0
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,I/BluetoothBondStateMachine( 2639): StableState(): Entering Off State
,D/BluetoothNotiBroadcastReceiver( 1308): onReceive
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5926): BTStateChangeCB is registed
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5926): BluetoothHeadset service is binded
D/GMFPReceiver( 5926): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5926): jangil::setProperties()
,D/GMFPReceiver( 5926): jangil::printBTStatus()
,D/SettingsProvider( 1015): name = Wearable0001
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10098
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
D/GMFPReceiver( 5926): ::::::::Wearable0001::false
,D/SettingsProvider( 1015): name = Wearable0002
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10098
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/GMFPReceiver( 5926): ::::::::Wearable0002::false
,D/GMFPReceiver( 5926): onServiceConnected() : 1
D/GMFPReceiver( 5926): mBluetoothHeadset = true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,E/bt-btm  ( 2639): tBTM_SEC_DEV:0xa46aef04 rs_disc_pending=0
,W/bt-btif ( 2639): bta_dm_check_av:0
,W/bt-btif ( 2639): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2639): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2639): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2639): bta_dm_pm_ssr:2, lat:1200
,D/BluetoothSocket( 6103): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@2e14f182
,E/BluetoothRemoteDevices( 2639): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Incoming connection initialized (thread ID: 1087)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6103): Entering thread (ID: 1087)
,E/SMD     (  289): DCD OFF
,E/bt-btm  ( 2639): tBTM_SEC_DEV:0xa46aef04 rs_disc_pending=0
,W/bt-btif ( 2639): bta_dm_check_av:0
W/bt-btif ( 2639): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): onBytesRead: Read 77 bytes successfully (thread ID: 1087)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): onBytesWritten: 82 bytes successfully written (thread ID: 1087)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): removeThreadFromList: Removing thread with ID 1087
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Handshake thread disposed (thread ID: 1087)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6103): Exiting thread (ID: 1087)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
,I/io.jxcore.node.ConnectionHelper( 6103): onConnected: Incoming connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/io.jxcore.node.ConnectionHelper( 6103): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper( 6103): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6103): onConnected: Incoming socket thread, for peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], created successfully
,D/io.jxcore.node.ConnectionHelper( 6103): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 6103): Entering thread (ID: 1088)
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10338
,I/io.jxcore.node.IncomingSocketThread( 6103): Local host address: localhost/127.0.0.1, port: 43634
,D/io.jxcore.node.IncomingSocketThread( 6103): Setting local streams and starting stream copying threads...
,I/jxcore-log( 6103): 2016-01-05T00:48:31.337Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6103): 
,I/io.jxcore.node.StreamCopyingThread( 6103): setBufferSize: Setting buffer size to 8192 bytes,
I/io.jxcore.node.StreamCopyingThread( 6103): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6103): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6103): Exiting thread (ID: 1088)
D/io.jxcore.node.StreamCopyingThread( 6103): Entering thread (ID: 1090, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6103): Entering thread (ID: 1089, name: Sender)
,I/jxcore-log( 6103): 2016-01-05T00:48:32.279Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.284Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.287Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.291Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.362Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.365Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.370Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.399Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.403Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.406Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.410Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.440Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.445Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.496Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.530Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.535Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.539Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.570Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.576Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.579Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data,
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.583Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:48:32.620Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6103): 
,W/bt-btif ( 2639): invalid rfc slot id: 11
,W/io.jxcore.node.StreamCopyingThread( 6103): Either failed to read from the output stream or write to the input stream (thread ID: 1090, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6103): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 6103): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1088
,D/io.jxcore.node.IncomingSocketThread( 6103): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6103): doStop: Thread ID: 1090
D/io.jxcore.node.IncomingSocketThread( 6103): close: Stopping sending thread...,
I/io.jxcore.node.StreamCopyingThread( 6103): doStop: Thread ID: 1089
D/io.jxcore.node.IncomingSocketThread( 6103): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6103): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 6103): Either failed to read from the output stream or write to the input stream (thread ID: 1089, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6103): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 6103): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6103): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6103): closeBluetoothSocketAndStreams
W/io.jxcore.node.ConnectionHelper( 6103): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@d0ca093, channel: 6, state: CONNECTED
D/BluetoothSocket( 6103): close() this: android.bluetooth.BluetoothSocket@d0ca093, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2bff58d0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@9a860c9mSocket: android.net.LocalSocket@ea4a3ce impl:android.net.LocalSocketImpl@2556b2ef fd:FileDescriptor[109]
D/BluetoothSocket( 6103): Closing mSocket: android.net.LocalSocket@ea4a3ce impl:android.net.LocalSocketImpl@2556b2ef fd:FileDescriptor[109]
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@d0ca093, channel: 6, state: CLOSED
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@d0ca093, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6103): Exiting thread (ID: 1090, name: Receiver)
D/io.jxcore.node.ConnectionHelper( 6103): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6103): Exiting thread (ID: 1089, name: Sender)
I/jxcore-log( 6103): 2016-01-05T00:48:32.695Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6103): 
,E/Watchdog( 1015): !@Sync 21,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.,
,E/bt-btm  ( 2639): tBTM_SEC_DEV:0xa46aef04 rs_disc_pending=0
,W/bt-btif ( 2639): bta_dm_check_av:0
,W/bt-btif ( 2639): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2639): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 2639): RFCOMM_DisconnectInd LCID:0x4d
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/bt-btm  ( 2639): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2639): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1176): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver onReceive,
D/KnoxKeyguardUpdateMonitor( 1015): BroadcastReceiver ACTION_ACL_DISCONNECTED,
,V/BluetoothEventManager( 1308): Received android.bluetooth.device.action.ACL_DISCONNECTED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,E/BluetoothEventManager( 1308): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 1176): isGear1: device is not B1!
,D/BluetoothAdapterService( 2639): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f1a56b2
,D/BtConfig.SecureMode( 2639): isSecureModeOn:false
,D/SecContentProvider( 1015): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2639): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5980): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5980): Bluetooth Device Name: G3-1
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): setState: RESTARTING
,D/WifiP2pService( 1015): InactiveState{ what=139268 }
,I/wpa_supplicant( 1385): P2P-FIND-STOPPED 
,D/WifiP2pService( 1015): InactiveState{ what=147493 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1015): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): Start timer timeout, starting now...
,D/WifiP2pService( 1015): InactiveState{ what=139265 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139265 }
D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1385): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1015): discovery change broadcast true,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437,
I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiDisplayController( 1015): Received list of peers.,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): restart: Restarting...
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pService( 1015): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1015): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService( 1015): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1015): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 1015): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1015): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/WifiP2pManager( 6103): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service request added successfully
,E/SMD     (  289): DCD OFF
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 13 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/WifiP2pService( 1015): InactiveState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1015): P2pEnabledState discover services
,D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1385): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service discovery started successfully,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1015): InactiveState{ what=147477 },
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 },
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 13 device(s) discovered
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 13 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged,
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1413): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate,
V/EmergencyMode( 1413): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2639): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2639): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437,
D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 },
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 13 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,E/SMD     (  289): DCD OFF
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): InactiveState{ what=139283 },
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
,D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9197","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
I/io.jxcore.node.ConnectionHelper( 6103): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac,
W/io.jxcore.node.ConnectionHelper( 6103): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197] already in the list, will not add again
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 13 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9197]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 600s ago
,E/Watchdog( 1015): !@Sync 22,
,I/jxcore-log( 6103): timeout now
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): weAreDoneNow, resultArray.length: 4,
I/jxcore-log( 6103): 
I/jxcore-log( 6103): sendReportNow
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): done, now sending data to server
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): 2016-01-05T00:49:03.593Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6103): 
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1015): DefaultState{ what=139283 },
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 13 device(s) discovered,
D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad,
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
,D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): restart: Restarting...
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pManager( 6103): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiP2pService( 1015): DefaultState{ what=139283 },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service request added successfully
D/WifiP2pService( 1015): InactiveState{ what=139307 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139307 },
D/WifiP2pService( 1015): P2pEnabledState clear service request
D/WifiP2pService( 1015): InactiveState{ what=139301 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1015): P2pEnabledState add service request
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/WifiP2pService( 1015): InactiveState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1015): P2pEnabledState discover services
,D/WifiStateMachine( 1015): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1015): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1015): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1385): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service discovery started successfully
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437,
D/WifiP2pService( 1015): InactiveState{ what=147477 }
I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.,
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1015): InactiveState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true,
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiDisplayController( 1015): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
,D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 },
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/io.jxcore.node.ConnectionHelper( 6103): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 6103): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] is available
,I/jxcore-log( 6103): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT6440","peerAvailable":true}]
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): Found peer : samsung-SM-G900F_PT6440, Available: true
I/jxcore-log( 6103): 
I/jxcore-log( 6103): startWithNextDevice
I/jxcore-log( 6103): 
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/io.jxcore.node.ConnectionHelper( 6103): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper( 6103): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] already in the list, will not add again
,E/SMD     (  289): DCD OFF
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1015): DefaultState{ what=139283 },
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiDisplayController( 1015): Received list of peers.
,D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiDisplayController( 1015): Received list of peers.
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 13 device(s) discovered,
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 13 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,E/SMD     (  289): DCD OFF
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1015): InactiveState{ what=139283 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 13 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/WifiP2pService( 1015): InactiveState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1015): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4505","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
I/io.jxcore.node.ConnectionHelper( 6103): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
W/io.jxcore.node.ConnectionHelper( 6103): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505] already in the list, will not add again
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/wpa_supplicant( 1385): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462,
D/WifiP2pService( 1015): InactiveState{ what=147477 }
D/WifiP2pService( 1015): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1015): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1015): DefaultState{ what=139283 }
D/WifiDisplayController( 1015): Received list of peers.
D/WifiDisplayController( 1015):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiDisplayController( 1015):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1015): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1015):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1015):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4505], add/update: true
D/WifiDisplayController( 1015):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1015):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4505]
D/WifiDisplayController( 1015):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pService( 1015): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1015):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1015): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT9383]
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/jxcore-log( 6103): teardown,
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): testSendData stopped
I/jxcore-log( 6103): 
,I/io.jxcore.node.ConnectionHelper( 6103): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): shutdown
D/BluetoothSocket( 6103): close() in, this: android.bluetooth.BluetoothSocket@244931fc, channel: 6, state: LISTENING
D/BluetoothSocket( 6103): close() this: android.bluetooth.BluetoothSocket@244931fc, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1709eb35, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@254d4085mSocket: android.net.LocalSocket@176b2eda impl:android.net.LocalSocketImpl@37858f0b fd:FileDescriptor[110]
D/BluetoothSocket( 6103): Closing mSocket: android.net.LocalSocket@176b2eda impl:android.net.LocalSocketImpl@37858f0b fd:FileDescriptor[110]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6103): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6103): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6103): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6103): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): stop: Stopping peer discovery...,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6103): stop: Stopping services
D/WifiP2pService( 1015): InactiveState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): stop: Stopping P2P device discovery...
,D/WifiP2pService( 1015): P2pEnabledState{ what=139298 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): setState: NOT_INITIALIZED
D/WifiP2pService( 1015): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6103): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6103): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6103): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6103): setState: NOT_STARTED
,I/jxcore-log( 6103): StopBroadcasting went ok
I/jxcore-log( 6103): 
,D/WifiP2pService( 1015): InactiveState{ what=139268 }
I/wpa_supplicant( 1385): P2P-FIND-STOPPED 
,I/jxcore-log( 6103): 2016-01-05T00:49:27.147Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 6103): 
D/WifiP2pService( 1015): InactiveState{ what=139307 }
I/io.jxcore.node.ConnectionHelper( 6103): onConnectionManagerStateChanged: NOT_STARTED
D/WifiP2pService( 1015): P2pEnabledState{ what=139307 }
I/io.jxcore.node.ConnectionHelper( 6103): onDiscoveryManagerStateChanged: NOT_STARTED
D/WifiP2pService( 1015): P2pEnabledState clear service request
I/chromium( 6103): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
D/WifiP2pService( 1015): remove channel information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6103): Local services cleared successfully
D/WifiP2pService( 1015): InactiveState{ what=147493 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6103): P2P device discovery stopped successfully
D/WifiP2pService( 1015): P2pEnabledState{ what=147493 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6103): Service requests cleared successfully
D/WifiP2pService( 1015): discovery change broadcast false
,I/jxcore-log( 6103): ****TEST TOOK:  ms ****
I/jxcore-log( 6103): 
,I/jxcore-log( 6103): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6103): 
,D/AndroidRuntime( 6800): 
D/AndroidRuntime( 6800): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6800): CheckJNI is OFF
D/AndroidRuntime( 6800): readGMSProperty: start
D/AndroidRuntime( 6800): readGMSProperty: already setted!!
D/AndroidRuntime( 6800): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6800): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6800): readGMSProperty: end
D/AndroidRuntime( 6800): addProductProperty: start
,E/AffinityControl( 6800): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6800): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1015): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1015): START PACKAGE DELETE: observer{543057238}
D/PackageManager( 1015): pkg{<packageName>}
D/PackageManager( 1015): user{0}
D/PackageManager( 1015): caller{2000}
D/PackageManager( 1015): flags{3}
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1015): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1015): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1015): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1015): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1015): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1015): !@killApplicatoin: 10338, uninstall pkg
,I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
,I/ActivityManager( 1015): Killing 6103:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1015): Skipping PackageSetting{26013a36 com.example.hello/10346} due to missing metadata
,I/WindowState( 1015): WIN DEATH: Window{f5365ac u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1015): Focus left window: 6103
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8),
I/ActivityManager( 1015):   Force finishing activity ActivityRecord{92a0633 u0 com.test.thalitest/.MainActivity t20}
W/ActivityManager( 1015): Spurious death for ProcessRecord{19589d7 6103:com.test.thalitest/u0a338}, curProc for 6103: null
I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1015):   Force finishing activity ActivityRecord{92a0633 u0 com.test.thalitest/.MainActivity t20 f}
W/ActivityManager( 1015): Duplicate finish request for ActivityRecord{92a0633 u0 com.test.thalitest/.MainActivity t20 f}
,W/ActivityManager( 1015): CustomStartingWindow se packge removed so remove capture also
,D/InputDispatcher( 1015): Focused application released,
,I/art     ( 5980): Explicit concurrent mark sweep GC freed 26997(1337KB) AllocSpace objects, 6(96KB) LOS objects, 25% free, 6MB/8MB, paused 889us total 40.283ms
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 3850): Explicit concurrent mark sweep GC freed 3166(190KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 782us total 41.193ms
,E/SamsungIME( 1859): mOCRHelper is null
,W/GeofencerStateMachine( 1742): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.5.123: ( 3604): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 05 01:49:27 GMT+01:00 2016
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3604): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1015): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1015): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1015): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,I/KLMS-2.5.123: ( 3604): KLMSIntentService(): onCreate()
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3604): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3604): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/EnterpriseDeviceManagerService( 1015): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1015): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1015): no available spell checker services found,
,E/Zygote  ( 6813): MountEmulatedStorage()
E/Zygote  ( 6813): v2
I/libpersona( 6813): KNOX_SDCARD checking this for 10090
I/libpersona( 6813): KNOX_SDCARD not a persona
,I/SELinux ( 6813): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6813): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6813): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1015): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6813 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3604): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3604): KLMSIntentService(): PACKAGE_REMOVED
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.123: ( 3604): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.123: ( 3604): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 6813): TimaSignature is unavailable
,D/ActivityThread( 6813): Added TimaKeyStore provider
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RegisteredServicesCache( 1435): empty dynamic service
,D/elm:15121( 6813): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6813): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6813): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6813): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 74114(10MB) AllocSpace objects, 70(1125KB) LOS objects, 33% free, 24MB/37MB, paused 3.064ms total 244.553ms
,I/art     ( 1015): WaitForGcToComplete blocked for 241.713ms for cause Explicit
,D/elm:15121( 6813): ElmAgentService : onCreate()
,D/elm:15121( 6813): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6813): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6813): MDMBridge.getInstance()
D/elm:15121( 6813): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 6813): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 3604): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 3604): KLMSIntentService(): onDestroy()
,E/SMD     (  289): DCD OFF
,D/elm:15121( 6813): ElmAgentService : onDestroy().
,I/ActivityManager( 1015): Killing 5004:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1015): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService( 1015): PackageReceiver onReceive()
,I/HarmonyEASService( 1015): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1015): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 15249(728KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 10.347ms total 180.343ms
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1015): clearDefaults: com.test.thalitest
,I/CrashAnrDetector( 1015): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1015): failed to open /acct/uid_10039/pid_5004/cgroup.procs: No such file or directory
,D/PackageManager( 1015): delete codoeFile: 
,D/AASAuninstall( 1015): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
,I/AASA_removePackage( 1015): UID=10338 Target=com.test.thalitest
,D/PackageManager( 1015): result of delete: 1{543057238}
,D/AndroidRuntime( 6800): Shutting down VM
,D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 1015): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10338
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10338
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
D/SSRM:aZ ( 1015): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
D/TaskPersister( 1015): removeObsoleteFile: deleting file=20_task.xml
,I/PCWCLIENTTRACE_PushUtil( 5682): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5682): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5682): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5682): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6830): MountEmulatedStorage()
,I/libpersona( 6830): KNOX_SDCARD checking this for 10029
E/Zygote  ( 6830): v2
I/libpersona( 6830): KNOX_SDCARD not a persona
I/SELinux ( 6830): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6830 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 6830): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6830): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6830): TimaSignature is unavailable,
,D/ActivityThread( 6830): Added TimaKeyStore provider
,I/SA      ( 5766): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5766): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager( 1015): Killing 5851:com.wsomacp/u0a23 (adj 15): empty #31
,I/FeatureConfig( 6830): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6830): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6830): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/Zygote  ( 6848): MountEmulatedStorage()
E/Zygote  ( 6848): v2
I/libpersona( 6848): KNOX_SDCARD checking this for 10039
I/libpersona( 6848): KNOX_SDCARD not a persona
,I/SELinux ( 6848): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6848): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6848): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 6830): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6830): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 1015): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6848 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6830): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6830): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6848): TimaSignature is unavailable
,D/ActivityThread( 6848): Added TimaKeyStore provider
,W/ResourcesManager( 6830): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6830): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6848): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6848): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6848): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6848): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6848): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6848): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6848): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6830): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/art     ( 6800): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/libprocessgroup( 1015): failed to open /acct/uid_10023/pid_5851/cgroup.procs: No such file or directory
,W/ResourcesManager( 6830): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6830): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6830): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6830): system/finder_cp/cpdata.xml file not found
,E/SQLiteLog( 6848): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30),
,E/SQLiteDatabase( 6848): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase( 6848): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6848): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6848): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6848): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase( 6848): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase( 6848): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6848): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6848): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6848): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6848): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6848): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6848): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6848): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6848): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6848): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6848): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6848): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/NearbySource( 6848): Nearby Source Create!
D/NearbyContext( 6848): Nearby Context Create!
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6848): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 6848): Samsung link source created
,E/SQLiteLog( 6848): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,D/ContactProvider( 6848): getAllContactInfoList Start
,E/SQLiteDatabase( 6848): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase( 6848): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6848): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6848): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6848): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6848): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase( 6848): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase( 6848): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase( 6848): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
E/SQLiteDatabase( 6848): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
E/SQLiteDatabase( 6848): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 6848): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteDatabase( 6848): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6848): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6848): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6848): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6848): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6848): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6848): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6848): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6848): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper( 6848): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper( 6848): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6848): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6848): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6848): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6848): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6848): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6848): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6848): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6848): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6848): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6848): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper( 6848): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper( 6848): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper( 6848): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
E/SQLiteOpenHelper( 6848): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
E/SQLiteOpenHelper( 6848): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 6848): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteOpenHelper( 6848): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 6848): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 6848): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6848): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6848): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6848): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6848): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6848): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6848): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/SQLiteOpenHelper( 6848): Opened local.db in read-only mode
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}

```
