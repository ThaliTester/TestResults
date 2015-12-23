#### Test 54312298af2c956_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  292): DCD OFF
--------- beginning of system
V/AlarmManager( 1017): waitForAlarm result :4
I/BooksSync( 5995): Starting books sync for 61035162, extras: ade
I/BooksConfig( 5995): GmsCore Version = 7.8.99 (2134222-434)
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
E/BooksAccountManager( 5995): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5995): Soft error
E/BooksSync( 5995): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5995): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 5995): Sync error
E/BooksSync( 5995): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5995): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5995): Finished books sync
D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 154713, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,D/AndroidRuntime( 6062): 
D/AndroidRuntime( 6062): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6062): CheckJNI is OFF
D/AndroidRuntime( 6062): readGMSProperty: start
D/AndroidRuntime( 6062): readGMSProperty: already setted!!
D/AndroidRuntime( 6062): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6062): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6062): readGMSProperty: end
D/AndroidRuntime( 6062): addProductProperty: start
E/AffinityControl( 6062): AffinityControl: registerfunction enter
D/AndroidRuntime( 6062): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1017): mDVFSHelper.acquire()
D/FocusedStackFrame( 1017): Set to : 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6074 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 1480
E/Zygote  ( 6074): MountEmulatedStorage()
D/AndroidRuntime( 6062): Shutting down VM
E/Zygote  ( 6074): v2
I/libpersona( 6074): KNOX_SDCARD checking this for 10338
I/libpersona( 6074): KNOX_SDCARD not a persona
I/SELinux ( 6074): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6074): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, uhalitest
E/SELinux ( 6074): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6074): TimaSignature is unavailable
D/ActivityThread( 6074): Added TimaKeyStore provider
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1017): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1480): updateVisibility : ActivityRecord{358a80ca token=android.os.BinderProxy@305bfb76 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1480): onTrimMemory. Level: 20
I/WebViewFactory( 6074): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6074): Time to load native libraries: 1 ms (timestamps 5843-5844)
I/LibraryLoader( 6074): Expected native library version number "",actual native library version number ""
W/art     ( 6062): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6074): Binding Chromium to main looper Looper (main, tid 1) {87962e3}
,I/LibraryLoader( 6074): Expected native library version number "",actual native library version number ""
,I/chromium( 6074): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6074): Initializing chromium process, singleProcess=true
,W/art     ( 6074): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6074): ApplicationContext is null in ApplicationStatus
,W/chromium( 6074): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6074): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6074): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6074): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6074): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6074): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6074): Local Branch: 
I/Adreno-EGL( 6074): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6074): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6074):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/art     ( 6074): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6074): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6074): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6074): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6074): CordovaWebView is running on device made by: samsung
,W/art     ( 6074): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6074): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1017): Activity pause timeout for ActivityRecord{252750dd u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 6074): Render dirty regions requested: true
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,W/chromium( 6074): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6074): updateVisibility : ActivityRecord{10b1433c token=android.os.BinderProxy@be5830e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6074): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6074): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1017): Focus entered window: 6074
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 6074): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 6074): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6074): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6074): Enabling debug mode 0
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
,I/ActivityManager( 1017): Displayed Component not be shown by security: +674ms (total +40s783ms)
,W/ActivityManager( 1017): mDVFSHelper.release()
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{252750dd u0 com.test.thalitest/.MainActivity t20} time:156380,
,W/IInputConnectionWrapper( 6074): showStatusIcon on inactive InputConnection
,I/Timeline( 6074): Timeline: Activity_idle id: android.os.BinderProxy@be5830e time:156385
,I/SurfaceFlinger(  258): id=12 Removed uhalitest (7/9)
,I/SurfaceFlinger(  258): id=12 Removed uhalitest (-2/9)
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1847): getCurrentCandidateView
,D/SamsungIME( 1847): Dismiss ExpandCandiate
,I/SamsungIME( 1847): getDebugLevel  : 0x4f4c,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/SamsungIME( 1847): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1847): KeybaordView init() : load resources
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,I/SamsungIME( 1847): getCurrentKeyboard
I/SamsungIME( 1847): getTextKeyboard
,D/SamsungIME( 1847): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/BindingManager( 6074): Cannot call determinedVisibility() - never saw a connection for the pid: 6074
,D/JsMessageQueue( 6074): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6074): JniHelper::setJavaVM(0xb735d448), pthread_self() = -1215601800
,D/JX-Cordova( 6074): jxcore cordova android initializing
,E/SMD     (  292): DCD OFF
D/SSRM:n  ( 1017): SIOP:: AP = 290
,W/jxcore-log( 6074): Initializing JXcore engine
W/jxcore-log( 6074): JXcore engine is ready
,W/jxcore-log( 6074): Starting JXcore engine
,E/audit   ( 1843): type=1400 msg=audit(1450836522.372:205): avc:  denied  { ioctl } for  pid=6074 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1843):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1843): type=1300 msg=audit(1450836522.372:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=2 a3=be81fd58 items=0 ppid=308 ppcomm=main pid=6074 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1843): type=1320 msg=audit(1450836522.372:205): 
,W/jxcore-log( 6074): Platform android
W/jxcore-log( 6074): 
W/jxcore-log( 6074): Process ARCH arm
W/jxcore-log( 6074): 
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/jxcore-log( 6074): JXcore Cordova bridge is ready!
I/jxcore-log( 6074): 
,W/jxcore-log( 6074): JXcore engine is started
,I/Choreographer( 6074): Skipped 125 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6074): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF,
,I/jxcore-log( 6074): Toggling radios to true,
I/jxcore-log( 6074): 
,D/BluetoothAdapter( 6074): enable()
,D/BluetoothAdapter( 6074): enable(): BT is already enabled..!,
,D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1017): mCursor = null
,D/WifiService( 1017): setWifiEnabled: true pid=6074, uid=10338
,W/ActivityManager( 1017): Permission Denial: getCurrentUser() from pid=6074, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1017): Failed getting userId using ActivityManagerNative,
W/WifiService( 1017): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6074, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1017): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1017): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1017): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1017): ,	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1017): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1017): name = wifi_on
,I/WifiService( 1017): disconnect: pid=6074, uid=10338
I/wpa_supplicant( 1399): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 6074): Radios toggled
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): Got Device Bluetooth address: 08:EC:A9:50:75:41,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): Perf Test app loaded loaded
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): check test folder
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): found test : ./testFindPeers.js
I/jxcore-log( 6074): 
,I/wpa_supplicant( 1399): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1399): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1399): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1399): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1399): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/wpa_supplicant( 1399): Cmd 35605 not handled
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
E/WifiStateMachine( 1017): WifiStateMachine: Leaving Connected state
D/Tethering( 1017): InitialState.processMessage what=4
,I/wpa_supplicant( 1399): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1399): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1399): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1399): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1399): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1399): First Scan Start
I/wpa_supplicant( 1399): Scan requested (ret=0) - scan timeout 30 seconds
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/Tethering( 1017): No numeric data
,D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering( 1017): clearTetheredNotification()
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/HotspotTile( 1178): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
D/HotspotTile( 1178): updateTetherState():false, false
,E/WifiNative-wlan0( 1017): do suspend true
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,I/jxcore-log( 6074): found test : ./testSendData.js
I/jxcore-log( 6074): 
,D/CommandListener(  279): Clearing all IP addresses on wlan0,
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/NetworkStats( 1017): performPollLocked() took 19ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,V/NativeCrypto( 1686): Read error: ssl=0xb7810a20: I/O error during system call, Connection timed out
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1017): updateNetworkInfo()
,D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,V/NativeCrypto( 1686): SSL shutdown failed: ssl=0xb7810a20: I/O error during system call, Broken pipe
,E/WifiStateMachine( 1017): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1399): wlan0: Setting scan request: 0 sec 0 usec
,I/rmt_storage(  271): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb89317c8
I/rmt_storage(  271): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  271): wakelock acquired: 1, error no: 42
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1198319480)
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
E/WifiNative-wlan0( 1017): do suspend true
,D/ConnectivityService( 1017): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService( 1017): InactiveState{ what=143375 }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Forcing reevaluation
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1017): Tagging socket 338 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
,I/qtaguid ( 1017): Untagging socket 338
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/jxcore-log( 6074): found test : ./testSendData2.js
I/jxcore-log( 6074): 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
I/Hs20UtilService( 2116): Starting #8
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/Hs20UtilService( 2116): Message received 5007
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1318): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1318): MountReceiver.mPrefHandler - 7002
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1198319480) wakelock released: 1, error no: 0
I/rmt_storage(  271): 
,I/rmt_storage(  271): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb89317c8
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6132 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/Zygote  ( 6132): MountEmulatedStorage()
E/Zygote  ( 6132): v2
I/libpersona( 6132): KNOX_SDCARD checking this for 10102
I/libpersona( 6132): KNOX_SDCARD not a persona
,I/SELinux ( 6132): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener(  279): Clearing all IP addresses on wlan0
D/ConnectivityService( 1017): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1017): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
I/SELinux ( 6132): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/ConnectivityService( 1017): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1017): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1017): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
E/SELinux ( 6132): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1462): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1462): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
D/WifiNetworkAgent( 1017): NetworkAgent: NetworkAgent channel lost
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-10ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1017): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): doQuit - quitNow()
,D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1017): MasterInitialState.processMessage what=3
,V/NetworkStats( 1017): updateIfacesLocked()
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
D/TimaKeyStoreProvider( 6132): TimaSignature is unavailable
D/ActivityThread( 6132): Added TimaKeyStore provider
V/NetworkStats( 1017): performPollLocked() took 3ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1178): EthernetConnected: false
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1178): updateDataNetType()
D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1178): updateLTEICONDataNetType:0
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,I/Choreographer( 6074): Skipped 107 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6074): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ResourcesManager( 6132): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3,
D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3,
D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,I/Babel_SMS( 6132): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6132): MmsConfig.loadMmsSettings
I/Babel_SMS( 6132): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,I/Babel_SMS( 6132): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6132): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6132): MmsConfig.loadFromResources
,E/Babel_SMS( 6132): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6132): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  284): getCameraInfo: X
,W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  284): getCameraInfo: X
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
W/Settings( 6132): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6132): startup - clean
,I/Babel   ( 6132): deleted: false for 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1017): updateDataUsageMap
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2116): Starting #9
,I/Hs20UtilService( 2116): Message received 5007
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1318): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1318): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6132): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6132): Unsupported mime audio/evrc
,W/AudioCapabilities( 6132): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6132): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6132): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6132): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6132): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6132): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6132): Unsupported mime audio/evrc
,W/VideoCapabilities( 6132): Unsupported mime video/wvc1
,W/VideoCapabilities( 6132): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6132): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6132): Unsupported mime video/wvc1
,W/VideoCapabilities( 6132): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6132): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6132): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6132): Unsupported mime video/mp43
,W/VideoCapabilities( 6132): Unsupported mime video/sorenson
,W/VideoCapabilities( 6132): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6132): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6132): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6132): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6132): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6132): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1017): Killing 5170:com.google.android.gm/u0a99 (adj 15): empty #31
,I/vclib   ( 6132): onServiceConnected
,W/Babel   ( 6132): Attempted to change video mute state without an active call.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/wpa_supplicant( 1399): nl80211: Received scan results (3 BSSes),
I/wpa_supplicant( 1399): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1399): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1399): Trying to associate with  'G700'
,I/wpa_supplicant( 1399): Re-associate with C0.AA.48
I/wpa_supplicant( 1399): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 1399): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/WifiMonitor( 1017): didn't find BSSID Trying to associate with SSID 'NG700'
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/libprocessgroup( 1017): failed to open /acct/uid_10099/pid_5170/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
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
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
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
,I/PCWCLIENTTRACE_PushUtil( 5651): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5651): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5651): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5651): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1017): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1017): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
,I/splitIntent( 1017): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5651): noConnectivity : true
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6176): MountEmulatedStorage()
I/libpersona( 6176): KNOX_SDCARD checking this for 10108
E/Zygote  ( 6176): v2
I/libpersona( 6176): KNOX_SDCARD not a persona
,I/SELinux ( 6176): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6176 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6176): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6176): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6176): TimaSignature is unavailable
,D/ActivityThread( 6176): Added TimaKeyStore provider
,E/wpa_supplicant( 1399): Cmd 35605 not handled
,I/wpa_supplicant( 1399): wlan0: State: ASSOCIATING -> ASSOCIATED
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1399): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1399): Associated with C0.AA.48
,I/wpa_supplicant( 1399): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1399): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1399): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, true
D/Tethering( 1017): interfaceLinkStateChanged wlan0, true
D/Tethering( 1017): interfaceStatusChanged wlan0, true
,E/Tethering( 1017): No numeric data
,D/Tethering( 1017): sendTetherStateChangedBroadcast 1, 0, 0
I/wpa_supplicant( 1399): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/Tethering( 1017): clearTetheredNotification()
I/wpa_supplicant( 1399): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,I/wpa_supplicant( 1399): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,I/wpa_supplicant( 1399): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1399): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1399): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1399): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1399): Blacklist: Clear (temp) 
I/wpa_supplicant( 1399): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1017): interfaceLinkStateChanged wlan0, true
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, true
D/Tethering( 1017): interfaceStatusChanged wlan0, true
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit,
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/HotspotTile( 1178): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/HotspotTile( 1178): updateTetherState():false, false
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
V/NetworkStats( 1017): performPollLocked() took 4ms
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/WifiNative-wlan0( 1017): callSECApiVoid - ID [50]
,E/WifiConfigStore( 1017): setLastSelectedConfiguration -1
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1017): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService( 1017): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,D/CommandListener(  279): Setting iface cfg,
,E/WifiStateMachine( 1017): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1017): mCursor = null
,E/WifiNative-wlan0( 1017): do suspend false
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,I/MusicStore( 6176): Database version: 120
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6176): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6176): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6176): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ResourcesManager( 6176): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6176): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6176): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/dhcpcd  ( 6200): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
I/dhcpcd  ( 6200): version 5.5.6 starting
,E/dhcpcd  ( 6200): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,E/SQLiteLog( 1686): (10) POSIX Error : 11 SQLite Error : 3850
,W/ActivityThread( 6176): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6176): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@357c9f18: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6176): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6176): GMSCore installation verified
,I/ConfigStore( 6176): Config Database version: 1,
,I/dhcpcd  ( 6200): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6200): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6200): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6200): bssid match
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
I/dhcpcd  ( 6200): wlan0: rebinding lease of 192.168.1.132
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1017): getStreamVolume 3 index 70
,I/MediaRouter( 6176): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6176): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6211): MountEmulatedStorage(),
,I/libpersona( 6211): KNOX_SDCARD checking this for 10001,
,E/Zygote  ( 6211): v2,
I/libpersona( 6211): KNOX_SDCARD not a persona
I/SELinux ( 6211): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6211 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6211): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6211): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GHttpClientFactory( 6176): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/TimaKeyStoreProvider( 6211): TimaSignature is unavailable
,D/ActivityThread( 6211): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 6176): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1017): Killing 5582:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/Zygote  ( 6230): MountEmulatedStorage()
,E/Zygote  ( 6230): v2
I/libpersona( 6230): KNOX_SDCARD checking this for 1000
I/libpersona( 6230): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6230 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6230): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1017): Killing 4188:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/SELinux ( 6230): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6230): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  308): Explicit concurrent mark sweep GC freed 8701(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 695us total 31.134ms
,D/TimaKeyStoreProvider( 6230): TimaSignature is unavailable
,D/ActivityThread( 6230): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 693us total 21.280ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 684us total 19.717ms
,I/DIAGMON_AGENT( 6230): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1017): failed to open /acct/uid_10139/pid_5582/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10032/pid_4188/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6230): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,I/DIAGMON_AGENT( 6230): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,I/DIAGMON_AGENT( 6230): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6230): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6230): ./extraInfo: <unknown ssid>
W/DIAGMON_AGENT( 6230): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6246): MountEmulatedStorage()
,E/Zygote  ( 6246): v2
I/libpersona( 6246): KNOX_SDCARD checking this for 10008
I/libpersona( 6246): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6246 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1017): Killing 5244:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/SELinux ( 6246): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6246): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6246): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6246): TimaSignature is unavailable
,D/ActivityThread( 6246): Added TimaKeyStore provider
,I/dhcpcd  ( 6200): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,I/ActivityManager( 1017): Killing 5625:com.samsung.helphub/1000 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3681): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 23 03:08:46 GMT+01:00 2015
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3681): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): onCreate()
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 6200): wlan0: leased 192.168.1.132 for 86400 seconds
,I/KLMS-2.5.123: ( 3681): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
W/libprocessgroup( 1017): failed to open /acct/uid_10014/pid_5244/cgroup.procs: No such file or directory
,I/KLMS-2.5.123: ( 3681): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/ActivityManager( 1017): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6264 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.123: ( 3681): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
E/Zygote  ( 6264): MountEmulatedStorage()
,E/Zygote  ( 6264): v2
I/libpersona( 6264): KNOX_SDCARD checking this for 10031
I/libpersona( 6264): KNOX_SDCARD not a persona
I/SELinux ( 6264): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6264): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6264): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3681): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3681): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): onDestroy(),
,D/TimaKeyStoreProvider( 6264): TimaSignature is unavailable,
D/ActivityThread( 6264): Added TimaKeyStore provider
,I/SO_AGENT( 6264): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available,
,I/DBG_POLICYDM( 5697): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5697): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/SA      ( 5840): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5840): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ],
I/DBG_POLICYDM( 5697): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
I/SA      ( 5840): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,E/DBG_POLICYDM( 5697): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5625/cgroup.procs: No such file or directory
,E/DBG_POLICYDM( 5697): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 5840): [SLFUCHKMGR] constructor called,
,I/SA      ( 5840): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5840): [OR] == isSIMCardReady false ==
,I/SA      ( 5840): [SCU] == networkStateCheck == false
I/SA      ( 5840): [OR] onReceive END
,I/ActivityManager( 1017): Killing 5151:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE,
,D/accuweather( 1602): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1659): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1602): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1602): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1602): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1602): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1602): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1602): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6300): MountEmulatedStorage()
,E/Zygote  ( 6300): v2
I/libpersona( 6300): KNOX_SDCARD checking this for 10121
I/libpersona( 6300): KNOX_SDCARD not a persona
,I/SELinux ( 6300): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6300): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6300 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 6300): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6300): TimaSignature is unavailable
,D/ActivityThread( 6300): Added TimaKeyStore provider
,W/ResourcesManager( 6300): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6300): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6300): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6300): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6300): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6300): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6315): MountEmulatedStorage(),
E/Zygote  ( 6315): v2
I/libpersona( 6315): KNOX_SDCARD checking this for 10141
I/libpersona( 6315): KNOX_SDCARD not a persona
I/SELinux ( 6315): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/libprocessgroup( 1017): failed to open /acct/uid_10032/pid_5151/cgroup.procs: No such file or directory
,I/SELinux ( 6315): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6315): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6315 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 5666:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6315): TimaSignature is unavailable
,D/ActivityThread( 6315): Added TimaKeyStore provider
,W/ResourcesManager( 6315): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6315): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6315): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6315): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/WifiNative-wlan0( 1017): do suspend true
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1017): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK,
E/WifiStateMachine( 1017): VerifyingLinkState enter
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1017): callSECApiInt - ID [210]
E/ConnectivityService( 1017): updateNetworkInfo()
,D/ConnectivityService( 1017): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1017): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1017): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1017): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1017): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1017): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1017): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1017): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1017): LTETest block dns file not exists
E/WifiStateMachine( 1017): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/ConnectivityService( 1017): updateNetworkInfo()
,E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1017): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
D/RCPManagerService( 1017): exchangeData() failure , invalid userId
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService( 1017):    accepting network in place of null
D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1462): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/TelephonyNetworkFactory( 1462): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 1017): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1017): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1017): mBoosterFLAG : 0
I/WifiTrafficPoller( 1017): current booster mode : FullMode
,D/WifiNative-wlan0( 1017): callSECApiVoid - ID [212],
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/ConnectivityService( 1017): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} },
D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE,
V/NetworkStats( 1017): updateIfacesLocked(),
D/Tethering( 1017): MasterInitialState.processMessage what=3,
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503],
D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
V/NetworkStats( 1017): performPollLocked() took 4ms
D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524290
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1178): EthernetConnected: false
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1178): updateDataNetType()
D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1178): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,W/libprocessgroup( 1017): failed to open /acct/uid_10087/pid_5666/cgroup.procs: No such file or directory
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/System.out( 1017): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/BadgeProvider( 5769): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/BadgeProvider( 5769): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5769): sendNotify, [notify] : null
,D/BadgeProvider( 5769): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5769): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5769): update, [UpdateCount] : 1
D/Launcher.Model( 1480): reloadBadges entered.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Dec 2015 02:08:47 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450836527455], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450836527433]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
,D/ConnectivityService( 1017): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1178): EthernetConnected: false
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1178): updateDataNetType()
D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1178): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6343): MountEmulatedStorage()
,I/libpersona( 6343): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6343): v2
I/libpersona( 6343): KNOX_SDCARD not a persona
I/SELinux ( 6343): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6343 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6343): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6343): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6343): TimaSignature is unavailable
,D/ActivityThread( 6343): Added TimaKeyStore provider
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SecurityLogAgent( 6343): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6343): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6343): StateMachine : Current State = 1
,D/SecurityLogAgent( 6343): StateMachine : Changed Current State = 1
,E/SMD     (  292): DCD OFF
,I/ActivityManager( 1017): Killing 5260:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 66113(3MB) AllocSpace objects, 10(212KB) LOS objects, 33% free, 23MB/35MB, paused 2.715ms total 176.910ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/ChimeraCfgMgr( 1967): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1967): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6366): MountEmulatedStorage()
,E/Zygote  ( 6366): v2
I/libpersona( 6366): KNOX_SDCARD checking this for 10032
I/libpersona( 6366): KNOX_SDCARD not a persona
I/SELinux ( 6366): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6366): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6366): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6366 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/System.out( 6132): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6132): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6132): (HTTPLog)-Static: isShipBuild true
I/System.out( 6132): (HTTPLog)-Thread-1046-260509596: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6132): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10102
,D/TimaKeyStoreProvider( 6366): TimaSignature is unavailable
,D/ActivityThread( 6366): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10029/pid_5260/cgroup.procs: No such file or directory
,I/System.out( 6132): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/art     ( 1686): Explicit concurrent mark sweep GC freed 22037(1290KB) AllocSpace objects, 5(101KB) LOS objects, 39% free, 7MB/12MB, paused 1.212ms total 50.164ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 6132): connection state changed from UNKNOWN to CONNECTED
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SPPClientService( 6366): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6366): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6366): [SystemStateMoniter] Current Time : 163545
,E/SPPClientService( 6366): [PushClientApplication] Push log off : This is Ship build version
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SPPClientService( 6366): [SystemStateMoniter] No Connect : true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6366): PushLog.txt file is not deleted.
,D/SPPClientService( 6366): PushLog.txt file is not deleted.
,D/SPPClientService( 6366): ============PushLog. stop!
,E/Zygote  ( 6385): MountEmulatedStorage(),
I/libpersona( 6385): KNOX_SDCARD checking this for 10110
E/Zygote  ( 6385): v2
I/libpersona( 6385): KNOX_SDCARD not a persona
,I/SELinux ( 6385): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6385 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 5718:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SELinux ( 6385): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6385): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/SPPClientService( 6366): [[SystemStateMonitorService]] No Active Internet
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/TimaKeyStoreProvider( 6385): TimaSignature is unavailable
D/ActivityThread( 6385): Added TimaKeyStore provider
,W/Kids    ( 1967): [AccountUtils] Account not ready
W/Kids    ( 1967): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1967): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1967): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1967): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1967): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1967): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1967): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1967): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1967): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1967): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1967): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1967): 	at java.lang.Thread.run(Thread.java:818)
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,I/NetworkMonitor( 6176): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,W/libprocessgroup( 1017): failed to open /acct/uid_10148/pid_5718/cgroup.procs: No such file or directory
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6385): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6385): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6385): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6385):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6385):   adb logcat -s GAv4
,W/GAv4    ( 6385): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6385): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6385): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6385): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6385): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6385): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6385): Time to load native libraries: 2 ms (timestamps 3989-3991)
I/LibraryLoader( 6385): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6385): Binding Chromium to main looper Looper (main, tid 1) {187ecdff}
,I/LibraryLoader( 6385): Expected native library version number "",actual native library version number ""
,I/chromium( 6385): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6385): Initializing chromium process, singleProcess=true
,W/art     ( 6385): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6385): ApplicationContext is null in ApplicationStatus
,W/chromium( 6385): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6385): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6385): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6385): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6385): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6385): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6385): Local Branch: 
I/Adreno-EGL( 6385): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6385): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6385):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/ConnectivityService( 1017): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,W/AudioManagerAndroid( 6385): Requires BLUETOOTH permission
,I/NSApplication( 6385): Starting up...
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6441): MountEmulatedStorage()
,E/Zygote  ( 6441): v2
I/libpersona( 6441): KNOX_SDCARD checking this for 10077
I/SELinux ( 6441): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 6441): KNOX_SDCARD not a persona
I/SELinux ( 6441): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6441 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5618:com.android.mms/u0a41 (adj 15): empty #31
I/ActivityManager( 1017): Killing 5741:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #32
,E/SELinux ( 6441): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6441): TimaSignature is unavailable
,D/ActivityThread( 6441): Added TimaKeyStore provider
,D/CountryDetector( 1017): No listener is left
,D/WaitQueueForNetworkActivate( 5967): notifyNetworkActivated
,W/libprocessgroup( 1017): failed to open /acct/uid_10041/pid_5618/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10152/pid_5741/cgroup.procs: No such file or directory
,W/ContextImpl( 5967): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1017): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5967): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5967): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5967): exit::IDLE
D/InitializeManagerStateMachine( 5967): entry::NETWORK_CHECK
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/InitializeManagerStateMachine( 5967): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5967): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5967): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5967): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5967): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5967): entry::SUCCESS
D/hcjo    ( 5967): AutoUpdateManager:INITCHECK:onInitializeSuccess
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2116): Starting #10
,I/Hs20UtilService( 2116): Message received 5007
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
,D/hcjo    ( 5967): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5967): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5967): exit::SUCCESS
D/InitializeManagerStateMachine( 5967): entry::IDLE
,I/ActivityManager( 1017): Killing 5785:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2116): Starting #11
,I/Hs20UtilService( 2116): Message received 5007
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2116): Starting #12
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1318): DMSUtil.isNetworkConnected - flag-null, state-null
I/Hs20UtilService( 2116): Message received 5007
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1318): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1318): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1318): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1318): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 2116): Starting #13
,I/Hs20UtilService( 2116): Message received 5007
,D/WifiStateMachine( 1017): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1017): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5651): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5651): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5651): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5651): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1017): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1017): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1017): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6176): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT( 6230): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6230): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6230): ./extraInfo: "NG700"
I/DIAGMON_AGENT( 6230): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService( 1017): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,D/SRIB_DCS( 1178): log_dcs ThreadedRenderer::initialize entered! 
,W/libprocessgroup( 1017): failed to open /acct/uid_10042/pid_5785/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5697): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5697): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5697): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5697): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5697): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5697): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6246): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6246): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 3681): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 23 03:08:49 GMT+01:00 2015
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3681): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): onCreate(),
,I/KLMS-2.5.123: ( 3681): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3681): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3681): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3681): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3681): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.5.123: ( 3681): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3681): StateImplV2(): networkChangeListener().END
,I/DBG_POLICYDM( 5697): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): onDestroy()
,D/ConnectivityService( 1017): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
I/DBG_POLICYDM( 5697): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524295
,I/DBG_POLICYDM( 5697): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,I/SA      ( 5840): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524295
I/SA      ( 5840): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5840): [OR] == ACTION_CONNECTIVITY_CHANGE ==
E/DBG_POLICYDM( 5697): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 5840): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5840): [OR] == isSIMCardReady false ==
,I/SA      ( 5840): [SCU] == networkStateCheck == true
I/SA      ( 5840): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5840): isChinaCountryCode : false
I/SA      ( 5840): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5840): [OR] == networkStateCheck true ==
,I/SA      ( 5840): [OR] GetMyCountryZoneTask
,I/SA      ( 5840): [OR] onReceive END
I/DBG_POLICYDM( 5697): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 5840): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/SA      ( 5840): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5840): [SSP] query invoked
,D/accuweather( 1602): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1659): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 1
,I/DBG_POLICYDM( 5697): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,D/accuweather( 1602): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1602): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1602): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1602): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5697): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5697): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/SA      ( 5840): [TPMU] GetMccFromDB : null
I/SA      ( 5840): [SCU] getMccFromPreferece mcc = 260
,I/DBG_POLICYDM( 5697): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5697): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/SA      ( 5840): [TPM] isNoProxy(default) : true
,I/DBG_POLICYDM( 5697): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
D/accuweather( 1602): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1602): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
D/SecContentProvider2( 1017): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1017): mCursor = null
I/DBG_POLICYDM( 5697): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5697): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5697): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/QuickConnect( 6300): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,E/File    ( 5840): fail readDirectory() errno=2
I/QuickConnect( 6300): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6300): PeriphStartReceiver.onReceive - no need to start
,E/DBG_POLICYDM( 5697): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/DBG_POLICYDM( 5697): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5697): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/SecurityLogAgent( 6343): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6343): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6343): StateMachine : Current State = 1
,D/SecurityLogAgent( 6343): StateMachine : Changed Current State = 1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1967): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1967): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6366): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6366): [SystemStateMoniter] Current Time : 164987
,E/SPPClientService( 6366): [SystemStateMoniter] No Connect : false
,I/System.out( 6132): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5967): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5967): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5967): exit::IDLE
I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
D/InitializeManagerStateMachine( 5967): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5967): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5967): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5967): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5967): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5967): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5967): entry::SUCCESS
D/hcjo    ( 5967): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5967): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5967): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5967): exit::SUCCESS
D/InitializeManagerStateMachine( 5967): entry::IDLE
,I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Kids    ( 1967): [AccountUtils] Account not ready
W/Kids    ( 1967): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1967): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1967): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1967): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1967): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1967): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1967): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1967): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1967): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1967): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1967): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1967): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/SA      ( 5840): [RC New] Execute method=[GET] start
,I/SA      ( 5840): [RC New] Security=[true]
,I/System.out( 5840): Thread-995(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5840): Thread-995(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5840): Thread-995(ApacheHTTPLog):isShipBuild true
,I/System.out( 5840): Thread-995(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5840): Thread-995(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10036
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6074): BLE supported!!
I/jxcore-log( 6074): 
,I/SA      ( 5840): [RC New] [v2liruge] api execute + 643
,I/SA      ( 5840): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 5840): AsyncTask #1 calls detatch()
,I/SA      ( 5840): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5840): [OCP] update openData : PL,
I/SA      ( 5840): [TPMU] getNetworkMcc : 
I/SA      ( 5840): [SCU] saveMccToPreferece Start
I/SA      ( 5840): [SCU] RegionMCC : 260
,I/SA      ( 5840): [SSP] query invoked
,I/SA      ( 5840): [TPMU] GetMccFromDB : null,
I/SA      ( 5840): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5840): [SCU] saveMccToPreferece End
,I/SA      ( 5840): [RC New] executeRequest [v2liruge] end. 703
I/SA      ( 5840): [RC New] Execute end
,I/SA      ( 5840): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5840): [OR] GetMyCountryZoneTask Success
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/dhcpcd  ( 6200): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/GCM     ( 1686): Connected
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1686): Message class com.google.f.a.a.p
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
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 4811): callingUid 10011, callindPid: 4811
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6176): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6176): Stop autocaching.
,E/GmsUtils( 6176): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6176): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/SSRM:n  ( 1017): SIOP:: AP = 310
,E/Watchdog( 1017): !@Sync 5
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  258): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  258): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1017): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1017) eventTime = 168158
,D/PowerManagerService( 1017): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017 (0x0),
D/PowerManagerService( 1017): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1017, ws=WorkSource{10049}) (elapsedTime=3485)
,V/AlarmManager( 1017): waitForAlarm result :4
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5333): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5333): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5333): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  292): DCD OFF
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5651): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5651): [hasSamungAccount] - No Samsung Account,
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5651): [GetString-S]
,I/ReactiveServiceManager( 5651): Supported : 1
,D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1017): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1017): QSEECom_shutdown_app, app_id = 11
E/terrier ( 1017): handleString: Failed to handle string(-4)
,E/terrier ( 1017): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 5651): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5651): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5651): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5651): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5651): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5651): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 6200): wlan0: sending IPv6 Router Solicitation
,V/AlarmManager( 1017): waitForAlarm result :4
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 32869(1716KB) AllocSpace objects, 5(88KB) LOS objects, 33% free, 23MB/35MB, paused 2.468ms total 151.537ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1686): Vacuum at: now=1450836536109 tag=VacuumService
,I/GoogleURLConnFactory( 1686): Using platform SSLCertificateSocketFactory
,W/Uploader( 1686): No account for auth token provided
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1686): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1686): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1686): (HTTPLog)-Static: isShipBuild true
I/System.out( 1686): (HTTPLog)-Thread-196-741686398: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1686): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,I/System.out( 1686): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1686): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1686, getuid(): 10011
,I/qtaguid ( 1686): Tagging socket 61 with tag 120100000000{4609,0} for uid -1, pid: 1686, getuid(): 10011,
,W/Uploader( 1686): No account for auth token provided
,I/System.out( 1686): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1686): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1686, getuid(): 10011
,W/Uploader( 1686): No account for auth token provided
,I/System.out( 1686): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1686): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1686, getuid(): 10011
,W/Uploader( 1686):  no longer exists, so no auth token.
,I/System.out( 1686): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1686): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1686, getuid(): 10011
,E/SMD     (  292): DCD OFF
,W/Uploader( 1686): No account for auth token provided
,I/System.out( 1686): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1686): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1686, getuid(): 10011
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true,
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
,I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,E/Uploader( 1686): Failed to get auth token: User intervention required. Notification has been pushed.
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
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
,I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1686): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1686): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1686, getuid(): 10011
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1686): (10) POSIX Error : 11 SQLite Error : 3850
,I/dhcpcd  ( 6200): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6200): wlan0: no IPv6 Routers available
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5967): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5967): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5967): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5967): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5967): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5967): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5967): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5967): entry::IDLE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5967): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5967): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5967): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5967): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5967): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5967): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5967): entry::IDLE
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 105s ago
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1017): waitForAlarm result :4
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5333): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5333): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5333): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 6
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/Watchdog( 1017): !@Sync 7
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1017): [PWL] Off : 180s ago
,E/Watchdog( 1017): !@Sync 8
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 5995): Starting books sync for 61035162, extras: ade,
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 5995): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/PhoneStatusBar( 1178): Icon Only
,I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
,I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5995): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5995): Soft error
E/BooksSync( 5995): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5995): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 5995): Sync error
E/BooksSync( 5995): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5995): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5995): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 283091, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  292): DCD OFF
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,E/SQLiteLog( 1686): (10) POSIX Error : 11 SQLite Error : 3850
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 9
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 225s ago
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  292): DCD OFF
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1017): initializing...
,I/TLC_TIMA_PKM_initialize( 1017): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1017): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1017): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1017): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1017): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1017): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1017): Trustlet response is completed
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1017): stay LED for fully charged,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/Watchdog( 1017): !@Sync 10
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager( 1017): waitForAlarm result :4
,I/BooksSync( 5995): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 5995): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/SMD     (  292): DCD OFF
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5995): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5995): Soft error
E/BooksSync( 5995): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5995): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 5995): Sync error
E/BooksSync( 5995): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5995): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 5995): Finished books sync
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 315807, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 11
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/jxcore-log( 6074): Connected to the server!
I/jxcore-log( 6074): 
,I/chromium( 6074): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 275s ago
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1686): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1686): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1686): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1686): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1686): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1686): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1686): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 5333): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5333): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5333): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5333): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5333): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5333): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5333): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
,I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/System  ( 5333): Ignoring header User-Agent because its value was null.
,I/System.out( 5333): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5333): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5333): (HTTPLog)-Static: isShipBuild true
I/System.out( 5333): (HTTPLog)-Thread-903-160144258: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 5333): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10026
,I/System.out( 5333): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK,
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 12,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 330s ago
,E/Watchdog( 1017): !@Sync 13
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,V/AlarmManager( 1017): waitForAlarm result :4
,I/BooksSync( 5995): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 5995): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/BooksAccountManager( 5995): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5995): Soft error
E/BooksSync( 5995): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5995): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 5995): Sync error
E/BooksSync( 5995): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5995): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5995): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 408357, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 50290(3MB) AllocSpace objects, 104(1686KB) LOS objects, 33% free, 23MB/35MB, paused 2.418ms total 165.349ms
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1017): !@Sync 14
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 15
,I/PowerManagerService( 1017): [PWL] Off : 390s ago
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/jxcore-log( 6074): --- start :testFindPeers.js---,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): testFindPeers created [object Object]
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): serverPort is 8876
I/jxcore-log( 6074): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): start: Peer ID: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT4270
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6074): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6074): initialize: My bluetooth address is 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6074): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6074): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6074): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
,D/BluetoothSocket( 6074): bindListen(), new LocalSocket 
D/BluetoothSocket( 6074): bindListen(), new LocalSocket.getInputStream() 
,D/BluetoothSocket( 6074): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3203ef97
D/BluetoothSocket( 6074): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): start: OK
I/io.jxcore.node.ConnectionHelper( 6074): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): start: Peer ID: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT4270
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6074): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6074): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): start: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6074): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1017): InactiveState{ what=139292 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 1017): P2pEnabledState add service
,D/WifiP2pService( 1017): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 6074): start: OK
,I/jxcore-log( 6074): StartBroadcasting started ok
I/jxcore-log( 6074): 
I/chromium( 6074): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6074): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onWifiStateChanged: State changed to 2
I/io.jxcore.node.ConnectionHelper( 6074): onDiscoveryManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6074): Local service added successfully
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1399): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): setState: STARTED
D/WifiP2pService( 1017): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2,
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 1017): InactiveState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState add service request,
,D/WifiP2pManager( 6074): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service request added successfully
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState discover services,
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1399): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1399): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service discovery started successfully
,I/wpa_supplicant( 1399): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1399): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 6074): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911] is available
,I/jxcore-log( 6074): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT3911","peerAvailable":true}]
I/jxcore-log( 6074): 
I/jxcore-log( 6074): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 6074): 
I/jxcore-log( 6074): weAreDoneNow
I/jxcore-log( 6074): 
I/jxcore-log( 6074): done, now sending data to server
I/jxcore-log( 6074): 
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/bootchecker(  317): bootchecker wake up!!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1017): stay LED for fully charged,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 16
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): setState: RESTARTING
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/wpa_supplicant( 1399): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): Start timer timeout, starting now...
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1399): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1017): discovery change broadcast true,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 7E.18.23 p2p_dev_addr=7E.18.23 pri_dev_type=10-0050F204-5  ' A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): restart: Restarting...
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState clear service request
,D/WifiP2pManager( 6074): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,D/WifiP2pService( 1017): InactiveState{ what=139301 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service request added successfully
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
,E/SMD     (  292): DCD OFF,
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState discover services
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc,
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1399): USE_NETWORK : USE_NETWORK OFF
I/wpa_supplicant( 1399): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service discovery started successfully
,I/wpa_supplicant( 1399): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1399): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 5 device(s) discovered
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1017): DefaultState{ what=139283 }
I/wpa_supplicant( 1399): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7855","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 6074): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] is available
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
,I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 6074): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715] is available
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,E/SMD     (  292): DCD OFF
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
,D/io.jxcore.node.ConnectionHelper( 6074): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145] is available
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 7E.18.23 p2p_dev_addr=7E.18.23 pri_dev_type=10-0050F204-5  ' A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 },
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 8 device(s) discovered
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545],
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 6074): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] is available
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryMa,nager( 6074): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 6074): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] is available
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 17,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86,
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): restart: Restarting...
,D/WifiP2pService( 1017): InactiveState{ what=139301 },
,D/WifiP2pManager( 6074): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service request added successfully
,D/WifiP2pService( 1017): P2pEnabledState add service request
,E/SMD     (  292): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1399): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service discovery started successfully,
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911] already in the list, will not add again
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1003","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
,D/io.jxcore.node.ConnectionHelper( 6074): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003] is available,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715],
D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715] already in the list, will not add again
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 455s ago,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
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
,I/BooksSync( 5995): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 5995): GmsCore Version = 7.8.99 (2134222-434)
,E/SMD     (  292): DCD OFF
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1686): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1686): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1686): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1686): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1686): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5995): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5995): Soft error
E/BooksSync( 5995): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5995): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 5995): Sync error
E/BooksSync( 5995): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5995): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5995): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 538373, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 18
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): setState: RESTARTING
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/wpa_supplicant( 1399): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1017): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): Start timer timeout, starting now...
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiP2pService( 1017): InactiveState{ what=139265 }
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/wpa_supplicant( 1399): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): P2P device discovery started successfully
D/WifiP2pService( 1017): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
I/wpa_supplicant( 1399): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c,
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003], add/update: true,
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): P2pEnabledState clear service request
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145], add/update: true
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): restart: Restarting...
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiP2pService( 1017): InactiveState{ what=139301 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState add service request
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145],
D/WifiP2pManager( 6074): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service request added successfully
,E/SMD     (  292): DCD OFF
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
D/WifiP2pService( 1017): InactiveState{ what=147477 }
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 10 device(s) discovered
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145], add/update: true
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/W,ifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145], add/update: true
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,D/WifiP2pService( 1017): InactiveState{ what=139310 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1399): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service discovery started successfully,
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462,
D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab:, 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT8145]
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911] already in the list, will not add again
,V/AlarmManager( 1017): waitForAlarm result :4
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,I/Atfwd_Daemon(  322): Stop the daemon....,
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 19
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/jxcore-log( 6074): teardown
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): testFindPeers stopped
I/jxcore-log( 6074): 
,I/io.jxcore.node.ConnectionHelper( 6074): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): shutdown
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@1c0dee33, channel: 6, state: LISTENING
D/BluetoothSocket( 6074): close() this: android.bluetooth.BluetoothSocket@1c0dee33, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3203ef97, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ef425f0mSocket: android.net.LocalSocket@19237769 impl:android.net.LocalSocketImpl@6b205ee fd:FileDescriptor[109]
D/BluetoothSocket( 6074): Closing mSocket: android.net.LocalSocket@19237769 impl:android.net.LocalSocketImpl@6b205ee fd:FileDescriptor[109]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6074): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): stop: Stopping P2P device discovery...
D/WifiP2pService( 1017): InactiveState{ what=139298 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): setState: NOT_INITIALIZED,
D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onIsWifiPeerDiscoveryStartedChanged: false
D/WifiP2pService( 1017): P2pEnabledState clear service,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): stopWifiPeerDiscovery: Stopped
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6074): release: No more listeners, de-initializing...,
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6074): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6074): release: No more listeners, de-initializing...,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): setState: NOT_STARTED,
D/WifiP2pService( 1017): InactiveState{ what=139307 }
I/jxcore-log( 6074): StopBroadcasting went ok
I/jxcore-log( 6074): 
,D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
I/chromium( 6074): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6074): onConnectionManagerStateChanged: NOT_STARTED
,D/WifiP2pService( 1017): P2pEnabledState clear service request
I/io.jxcore.node.ConnectionHelper( 6074): onDiscoveryManagerStateChanged: NOT_STARTED
I/wpa_supplicant( 1399): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6074): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Exiting thread
,D/WifiP2pService( 1017): remove channel information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): onServerStopped
I/jxcore-log( 6074): --- start :testSendData.js---
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 0
I/jxcore-log( 6074): 
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1017): discovery change broadcast false
,I/jxcore-log( 6074): check server,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): serverPort is 57401
I/jxcore-log( 6074): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): start: Peer ID: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT4270
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6074): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6074): initialize: My bluetooth address is 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6074): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6074): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6074): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[110]},
,D/BluetoothSocket( 6074): bindListen(), new LocalSocket 
D/BluetoothSocket( 6074): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6074): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@70db11c
D/BluetoothSocket( 6074): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): start: OK
I/io.jxcore.node.ConnectionHelper( 6074): start: Using peer discovery mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): start: Peer ID: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT4270
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6074): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6074): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): start: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6074): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1017): InactiveState{ what=139292 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6074): start: OK
D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
D/WifiP2pService( 1017): P2pEnabledState add service
D/WifiP2pService( 1017): add a new client
I/jxcore-log( 6074): StartBroadcasting started ok
I/jxcore-log( 6074): 
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiP2pService( 1017): InactiveState{ what=139265 }
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/jxcore-log( 6074): null
I/jxcore-log( 6074): 
I/wpa_supplicant( 1399): USE_NETWORK : USE_NETWORK OFF
,I/jxcore-log( 6074): 2015-12-23T02:15:57.097Z SendDataTCPServer.js: TCP/IP server is bound to port: 57401
I/jxcore-log( 6074): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6074): onConnectionManagerStateChanged: RUNNING
D/WifiP2pService( 1017): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onWifiStateChanged: State changed to 2
I/io.jxcore.node.ConnectionHelper( 6074): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): restart: Restarting...
D/WifiP2pService( 1017): InactiveState{ what=139268 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6074): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): P2P device discovery started successfully
I/wpa_supplicant( 1399): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): setState: STARTED
D/WifiP2pService( 1017): InactiveState{ what=147493 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): P2P device discovery stopped successfully
D/WifiP2pService( 1017): P2pEnabledState{ what=147493 },
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/WifiP2pService( 1017): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): setState: RESTARTING
I/chromium( 6074): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): Start timer timeout, starting now...
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1399): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1017): discovery change broadcast true,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 },
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017): Received list of peers.
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac,
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b,:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pManager( 6074): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service request added successfully
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiP2pService( 1017): InactiveState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1399): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service discovery started successfully,
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4998","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
D/io.jxcore.node.ConnectionHelper( 6074): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] is available
,I/jxcore-log( 6074): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"motorola-XT1072_PT4998","peerAvailable":true}]
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): Found peer : motorola-XT1072_PT4998, Available: true
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): startWithNextDevice
I/jxcore-log( 6074): 
I/jxcore-log( 6074): device[1]: 44:80:EB:7B:5A:05
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:05.673Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:05.674Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 6074): 
I/jxcore-log( 6074): 2015-12-23T02:16:05.674Z SendDataConnector.js: do connect now
I/jxcore-log( 6074): 
,I/io.jxcore.node.ConnectionHelper( 6074): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 6074): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): connect: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): onConnecting: null 44:80:EB:7B:5A:05
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): connect: Started connecting to null in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 6074): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 1055)
,D/BluetoothUtils( 6074): isSocketAllowedBySecurityPolicy start : device null,
W/BluetoothAdapter( 6074): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2656): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/BluetoothSocket( 6074): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
,D/IOP_DB_BT( 2656): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 2656): db_query_execute: result 1
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 525s ago
,I/PowerManagerService( 1017): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1017): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=2656, ws=null) (elapsedTime=1420)
,D/IOP_DB_BT( 2656): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05,
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2656): db_query_execute: result 1
,W/bt-btif ( 2656): info:x10
D/        ( 2656): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 2656): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.NAME_CHANGED
,W/bt-sdp  ( 2656): process_service_search_attr_rsp
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 2656): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.CLASS_CHANGED,
D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2656): check_cod: remote_cod = 0x5a020c,
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,I/BluetoothBondStateMachine( 2656): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
D/BtConfig.SecureMode( 2656): isSecureModeOn:false
I/BluetoothBondStateMachine( 2656): Entering PendingCommandState State
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1178):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1318): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5895): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5895): BluetoothHeadset service is binded
,D/GMFPReceiver( 5895): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5895): jangil::setProperties()
,D/GMFPReceiver( 5895): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/btif_config_util( 2656): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10098
,I/BluetoothBondStateMachine( 2656): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2656): Failed to remove device: 44:80:EB:7B:5A:05
,D/GMFPReceiver( 5895): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2656): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 2656): isSecureModeOn:false
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10098
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5895): ::::::::Wearable0002::false
,D/GMFPReceiver( 5895): onServiceConnected() : 1
D/GMFPReceiver( 5895): mBluetoothHeadset = true
,D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1178):  handleUpdatestate:false name:null
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/HidService( 2656): getHidService(): returning com.android.bluetooth.hid.HidService@d3e2aa3
,D/SettingsProvider( 1017): name = bluetooth_input_device_priority_44:80:EB:7B:5A:05
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
W/bt-btif ( 2656): new conn_srvc id:26, app_id:1
W/bt-btif ( 2656): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2656): bta_dm_pm_ssr:2, lat:1200
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
,E/BluetoothRemoteDevices( 2656): setRfcommConnected true
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,D/HidService( 2656): Saved priority 44:80:EB:7B:5A:05 = -1
,D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_44:80:EB:7B:5A:05
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/SettingsProvider( 1017): name = bluetooth_headset_priority_44:80:EB:7B:5A:05
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): onSocketConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1055)
,I/BluetoothBondStateMachine( 2656): StableState(): Entering Off State
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): onBytesWritten: 83 bytes successfully written (thread ID: 1056)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): Outgoing connection initialized (*handshake* thread ID: 1056)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): Exiting thread (thread ID: 1055)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6074): Entering thread (ID: 1056)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1318): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5895): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5895): BluetoothHeadset service is binded
D/GMFPReceiver( 5895): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5895): jangil::setProperties()
,D/GMFPReceiver( 5895): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5895): ::::::::Wearable0001::false
D/SettingsProvider( 1017): name = Wearable0002
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5895): ::::::::Wearable0002::false
,D/GMFPReceiver( 5895): onServiceConnected() : 1
D/GMFPReceiver( 5895): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): onBytesRead: Read 81 bytes successfully (thread ID: 1056)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): onHandshakeSucceeded: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6074): Exiting thread (ID: 1056)
,I/io.jxcore.node.ConnectionHelper( 6074): onConnected: Outgoing connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,D/io.jxcore.node.ConnectionHelper( 6074): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6074): onConnected: Outgoing socket thread, for peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6074): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6074): Entering thread (ID: 1057)
,D/io.jxcore.node.OutgoingSocketThread( 6074): Server socket local port: 36263
I/io.jxcore.node.OutgoingSocketThread( 6074): Now accepting connections...
,E/SMD     (  292): DCD OFF
,I/io.jxcore.node.ConnectionHelper( 6074): onListeningForIncomingConnections: Outgoing connection is using port 36263 (peer ID: 44:80:EB:7B:5A:05)
,I/jxcore-log( 6074): 2015-12-23T02:16:08.866Z SendDataConnector.js: CLIENT connected to 36263, error: null
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:08.867Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6074): 
,I/io.jxcore.node.OutgoingSocketThread( 6074): Incoming data from address: /127.0.0.1, port: 36263
,D/io.jxcore.node.OutgoingSocketThread( 6074): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6074): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6074): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 6074): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6074): Exiting thread (ID: 1057)
,I/jxcore-log( 6074): 2015-12-23T02:16:08.882Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6074): 
,D/io.jxcore.node.StreamCopyingThread( 6074): Entering thread (ID: 1058, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6074): Entering thread (ID: 1059, name: Receiver)
,D/        ( 2656): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3786
,D/        ( 2656): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:22280
,I/jxcore-log( 6074): 2015-12-23T02:16:09.327Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6074): 
,D/        ( 2656): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:10400
,I/jxcore-log( 6074): 2015-12-23T02:16:09.370Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:09.388Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:09.392Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6074): 
,D/        ( 2656): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3470
,I/jxcore-log( 6074): 2015-12-23T02:16:09.424Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:09.464Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:09.468Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:09.506Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:09.510Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:09.550Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:09.550Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): oneRoundDownNow
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:09.554Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:09.554Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6074): 
,D/io.jxcore.node.ConnectionHelper( 6074): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
,I/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 44:80:EB:7B:5A:05
I/io.jxcore.node.OutgoingSocketThread( 6074): close
,D/io.jxcore.node.OutgoingSocketThread( 6074): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6074): doStop: Thread ID: 1059
,D/io.jxcore.node.OutgoingSocketThread( 6074): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6074): doStop: Thread ID: 1058
,D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6074): Either failed to read from the output stream or write to the input stream (thread ID: 1058, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 6074): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6074): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6074): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@2c6ef0ab, channel: 5, state: CONNECTED
,D/BluetoothSocket( 6074): close() this: android.bluetooth.BluetoothSocket@2c6ef0ab, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@7d2c308, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2c59aaa1mSocket: android.net.LocalSocket@db0e4c6 impl:android.net.LocalSocketImpl@3129ec87 fd:FileDescriptor[111]
,D/BluetoothSocket( 6074): Closing mSocket: android.net.LocalSocket@db0e4c6 impl:android.net.LocalSocketImpl@3129ec87 fd:FileDescriptor[111]
,W/io.jxcore.node.StreamCopyingThread( 6074): Either failed to read from the output stream or write to the input stream (thread ID: 1059, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6074): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 6074): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@2c6ef0ab, channel: 5, state: CLOSED,
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@2c6ef0ab, channel: 5, state: CLOSED
,D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 6074): disconnectOutgoingConnection: Successfully disconnected (peer ID: 44:80:EB:7B:5A:05
E/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
,D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6074): Exiting thread (ID: 1058, name: Sender)
,W/bt-btif ( 2656): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
E/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6074): Exiting thread (ID: 1059, name: Receiver)
,I/jxcore-log( 6074): 2015-12-23T02:16:09.575Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): ---- round done--------
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): startWithNextDevice
I/jxcore-log( 6074): 
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/bt-btm  ( 2656): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2656): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1178): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1318): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/KeyguardViewMediator( 1178): isGear1: device is not B1!
,D/BluetoothAdapterService( 2656): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cc83399,
D/BtConfig.SecureMode( 2656): isSecureModeOn:false
,D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/BluetoothPbapService( 2656): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5951): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5951): Bluetooth Device Name: XT1072
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/IOP_DB_BT( 2656): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2656): db_query_execute: result 1
,D/IOP_DB_BT( 2656): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2656): db_query_execute: result 1
,W/bt-btif ( 2656): info:x10
,D/        ( 2656): remote version info [7c:f9:0e:37:96:ab]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2656): aclStateChangeCallback: Device is NULL
,E/SMD     (  292): DCD OFF
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.NAME_CHANGED
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 2656): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.CLASS_CHANGED
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2656): check_cod: remote_cod = 0x5a020c
,D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 2656): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/BluetoothTile( 1178):  handleUpdatestate:false name:null
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
D/BtConfig.SecureMode( 2656): isSecureModeOn:false
I/BluetoothBondStateMachine( 2656): Entering PendingCommandState State
V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.BOND_STATE_CHANGED
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1318): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5895): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5895): BluetoothHeadset service is binded
D/GMFPReceiver( 5895): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5895): jangil::setProperties()
,D/GMFPReceiver( 5895): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5895): ::::::::Wearable0001::false
D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5895): ::::::::Wearable0002::false
D/GMFPReceiver( 5895): onServiceConnected() : 1
D/GMFPReceiver( 5895): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/btif_config_util( 2656): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2656): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2656): Failed to remove device: 7C:F9:0E:37:96:AB
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2656): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10,
D/BtConfig.SecureMode( 2656): isSecureModeOn:false
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
D/HidService( 2656): getHidService(): returning com.android.bluetooth.hid.HidService@d3e2aa3
V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
D/SettingsProvider( 1017): name = bluetooth_input_device_priority_7C:F9:0E:37:96:AB
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/HidService( 2656): Saved priority 7C:F9:0E:37:96:AB = -1
D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_7C:F9:0E:37:96:AB
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/BluetoothTile( 1178):  handleUpdatestate:false name:null
D/BluetoothNotiBroadcastReceiver( 1318): onReceive
,D/SettingsProvider( 1017): name = bluetooth_headset_priority_7C:F9:0E:37:96:AB
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,I/BluetoothBondStateMachine( 2656): StableState(): Entering Off State
,E/BluetoothHeadset( 5895): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5895): BluetoothHeadset service is binded
D/GMFPReceiver( 5895): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5895): jangil::setProperties()
,D/GMFPReceiver( 5895): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5895): ::::::::Wearable0001::false
D/SettingsProvider( 1017): name = Wearable0002
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5895): ::::::::Wearable0002::false
,D/GMFPReceiver( 5895): onServiceConnected() : 1
D/GMFPReceiver( 5895): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,W/bt-btif ( 2656): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2656): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2656): bta_dm_pm_ssr:2, lat:1200
,D/BluetoothSocket( 6074): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@2c5507b4
,E/BluetoothRemoteDevices( 2656): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Incoming connection initialized (thread ID: 1060)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6074): Entering thread (ID: 1060)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): onBytesRead: Read 83 bytes successfully (thread ID: 1060),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): onBytesWritten: 83 bytes successfully written (thread ID: 1060)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): removeThreadFromList: Removing thread with ID 1060
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Handshake thread disposed (thread ID: 1060)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6074): Exiting thread (ID: 1060)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/io.jxcore.node.ConnectionHelper( 6074): onConnected: Incoming connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/io.jxcore.node.ConnectionHelper( 6074): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
,W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6074): onConnected: Incoming socket thread, for peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], created successfully
,D/io.jxcore.node.ConnectionHelper( 6074): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 6074): Entering thread (ID: 1061)
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10338
,I/io.jxcore.node.IncomingSocketThread( 6074): Local host address: localhost/127.0.0.1, port: 57401
,I/jxcore-log( 6074): 2015-12-23T02:16:15.408Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6074): 
,D/io.jxcore.node.IncomingSocketThread( 6074): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6074): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6074): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6074): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6074): Exiting thread (ID: 1061)
,D/io.jxcore.node.StreamCopyingThread( 6074): Entering thread (ID: 1063, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6074): Entering thread (ID: 1062, name: Sender)
,I/jxcore-log( 6074): 2015-12-23T02:16:16.157Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.161Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.164Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.168Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.243Z SendDataTCPServer.js: TCP/IP server has received 10120 bytes of data,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.250Z SendDataTCPServer.js: TCP/IP server has received 12144 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.280Z SendDataTCPServer.js: TCP/IP server has received 22264 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.375Z SendDataTCPServer.js: TCP/IP server has received 24288 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.416Z SendDataTCPServer.js: TCP/IP server has received 26312 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.422Z SendDataTCPServer.js: TCP/IP server has received 28336 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.435Z SendDataTCPServer.js: TCP/IP server has received 30360 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.444Z SendDataTCPServer.js: TCP/IP server has received 32384 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.480Z SendDataTCPServer.js: TCP/IP server has received 42504 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.485Z SendDataTCPServer.js: TCP/IP server has received 44528 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.526Z SendDataTCPServer.js: TCP/IP server has received 46552 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.564Z SendDataTCPServer.js: TCP/IP server has received 48576 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.578Z SendDataTCPServer.js: TCP/IP server has received 50600 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.584Z SendDataTCPServer.js: TCP/IP server has received 52624 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.620Z SendDataTCPServer.js: TCP/IP server has received 60720 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.624Z SendDataTCPServer.js: TCP/IP server has received 62744 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.660Z SendDataTCPServer.js: TCP/IP server has received 66792 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.677Z SendDataTCPServer.js: TCP/IP server has received 68816 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.715Z SendDataTCPServer.js: TCP/IP server has received 70840 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.731Z SendDataTCPServer.js: TCP/IP server has received 72864 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.770Z SendDataTCPServer.js: TCP/IP server has received 85008 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.776Z SendDataTCPServer.js: TCP/IP server has received 87032 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.782Z SendDataTCPServer.js: TCP/IP server has received 89056 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.820Z SendDataTCPServer.js: TCP/IP server has received 93104 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.870Z SendDataTCPServer.js: TCP/IP server has received 95128 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.879Z SendDataTCPServer.js: TCP/IP server has received 97152 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:16.910Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6074): 
,W/bt-btif ( 2656): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 6074): Either failed to read from the output stream or write to the input stream (thread ID: 1063, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6074): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6074): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1061
D/io.jxcore.node.IncomingSocketThread( 6074): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 6074): doStop: Thread ID: 1063
D/io.jxcore.node.IncomingSocketThread( 6074): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6074): doStop: Thread ID: 1062
D/io.jxcore.node.IncomingSocketThread( 6074): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6074): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6074): Either failed to read from the output stream or write to the input stream (thread ID: 1062, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6074): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6074): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 6074): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6074): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6074): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@31c54fdd, channel: 6, state: CONNECTED
D/BluetoothSocket( 6074): close() this: android.bluetooth.BluetoothSocket@31c54fdd, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31468752, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@33aeca23mSocket: android.net.LocalSocket@3d14eb20 impl:android.net.LocalSocketImpl@1c4c0cd9 fd:FileDescriptor[109]
D/BluetoothSocket( 6074): Closing mSocket: android.net.LocalSocket@3d14eb20 impl:android.net.LocalSocketImpl@1c4c0cd9 fd:FileDescriptor[109]
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@31c54fdd, channel: 6, state: CLOSED
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@31c54fdd, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6074): Exiting thread (ID: 1063, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6074): Exiting thread (ID: 1062, name: Sender)
,I/jxcore-log( 6074): 2015-12-23T02:16:16.948Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6074): 
,W/bt-rfcomm( 2656): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 2656): RFCOMM_DisconnectInd LCID:0x43
,E/SMD     (  292): DCD OFF
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  292): DCD OFF
,D/IOP_DB_BT( 2656): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 2656): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2656): db_query_execute: result 1
,D/IOP_DB_BT( 2656): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 58:3f:54:73:64:c0
,D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 2656): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2656): db_query_execute: result 1
,W/bt-btif ( 2656): info:x10
,D/        ( 2656): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2656): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.NAME_CHANGED
,W/bt-btm  ( 2656): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 2656): tBTM_SEC_DEV:0xa46b17f4 rs_disc_pending=2
,W/bt-btif ( 2656): bta_dm_check_av:0
,W/bt-btif ( 2656): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2656): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2656): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1178): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.ACL_DISCONNECTED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,E/BluetoothEventManager( 1318): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/KeyguardViewMediator( 1178): isGear1: device is not B1!
,D/BluetoothAdapterService( 2656): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cc83399
D/BtConfig.SecureMode( 2656): isSecureModeOn:false
,D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2656): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5951): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5951): Bluetooth Device Name: A5-1
,E/Watchdog( 1017): !@Sync 20
,I/BluetoothBondStateMachine( 2656): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2656): check_cod: remote_cod = 0x5a020c
V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.NAME_CHANGED
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.CLASS_CHANGED
,I/BluetoothBondStateMachine( 2656): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2656): isSecureModeOn:false
I/BluetoothBondStateMachine( 2656): Entering PendingCommandState State
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1178):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1318): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5895): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5895): BluetoothHeadset service is binded
,D/GMFPReceiver( 5895): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5895): jangil::setProperties()
,D/GMFPReceiver( 5895): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5895): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5895): ::::::::Wearable0002::false
D/GMFPReceiver( 5895): onServiceConnected() : 1
D/GMFPReceiver( 5895): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/btif_config_util( 2656): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2656): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2656): Failed to remove device: 58:3F:54:73:64:C0
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2656): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2656): isSecureModeOn:false
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
,D/HidService( 2656): getHidService(): returning com.android.bluetooth.hid.HidService@d3e2aa3
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/SettingsProvider( 1017): name = bluetooth_input_device_priority_58:3F:54:73:64:C0
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/HidService( 2656): Saved priority 58:3F:54:73:64:C0 = -1
,D/BluetoothTile( 1178):  handleUpdatestate:false name:null
,D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_58:3F:54:73:64:C0
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/BluetoothNotiBroadcastReceiver( 1318): onReceive
,D/SettingsProvider( 1017): name = bluetooth_headset_priority_58:3F:54:73:64:C0,
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
I/BluetoothBondStateMachine( 2656): StableState(): Entering Off State
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5895): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5895): BluetoothHeadset service is binded
,D/GMFPReceiver( 5895): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5895): jangil::setProperties()
,D/GMFPReceiver( 5895): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5895): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5895): ::::::::Wearable0002::false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/GMFPReceiver( 5895): onServiceConnected() : 1
D/GMFPReceiver( 5895): mBluetoothHeadset = true
,W/bt-btif ( 2656): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2656): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2656): bta_dm_pm_ssr:2, lat:1200
,D/BluetoothSocket( 6074): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@121c69e
,E/BluetoothRemoteDevices( 2656): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Incoming connection initialized (thread ID: 1064)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6074): Entering thread (ID: 1064)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): onBytesRead: Read 77 bytes successfully (thread ID: 1064)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): onBytesWritten: 83 bytes successfully written (thread ID: 1064)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): removeThreadFromList: Removing thread with ID 1064
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Handshake thread disposed (thread ID: 1064)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6074): Exiting thread (ID: 1064)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
,I/io.jxcore.node.ConnectionHelper( 6074): onConnected: Incoming connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/io.jxcore.node.ConnectionHelper( 6074): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
,W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6074): onConnected: Incoming socket thread, for peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], created successfully
,D/io.jxcore.node.ConnectionHelper( 6074): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 6074): Entering thread (ID: 1065)
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10338
,I/io.jxcore.node.IncomingSocketThread( 6074): Local host address: localhost/127.0.0.1, port: 57401
,D/io.jxcore.node.IncomingSocketThread( 6074): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6074): setBufferSize: Setting buffer size to 8192 bytes,
I/io.jxcore.node.StreamCopyingThread( 6074): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6074): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6074): Exiting thread (ID: 1065)
,I/jxcore-log( 6074): 2015-12-23T02:16:22.510Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6074): 
D/io.jxcore.node.StreamCopyingThread( 6074): Entering thread (ID: 1067, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 6074): Entering thread (ID: 1066, name: Sender)
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,I/jxcore-log( 6074): 2015-12-23T02:16:23.519Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:23.523Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:23.526Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:23.530Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:23.534Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:23.538Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:23.541Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:23.580Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:23.592Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:23.630Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 6074): 
,D/IOP_DB_BT( 2656): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
,D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_VER, value 0:0
,D/IOP_DB_BT( 2656): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2656): db_query_execute: result 1
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/IOP_DB_BT( 2656): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:51:18:22
,D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2656): db_query_execute: result 1
,W/bt-btif ( 2656): info:x10
,D/        ( 2656): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2656): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 6074): 2015-12-23T02:16:23.958Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:23.990Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:23.994Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:24.030Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 6074): 
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.NAME_CHANGED
,I/jxcore-log( 6074): 2015-12-23T02:16:24.051Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:24.058Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:24.069Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:24.111Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:24.150Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:24.157Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:24.166Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:24.206Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:24.215Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:24.269Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:24.275Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:24.282Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:24.320Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:24.356Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:24.360Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:24.400Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6074): 
,W/bt-btif ( 2656): invalid rfc slot id: 7
,W/io.jxcore.node.StreamCopyingThread( 6074): Either failed to read from the output stream or write to the input stream (thread ID: 1067, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6074): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6074): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1065
D/io.jxcore.node.IncomingSocketThread( 6074): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 6074): doStop: Thread ID: 1067
,D/io.jxcore.node.IncomingSocketThread( 6074): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6074): doStop: Thread ID: 1066
,D/io.jxcore.node.IncomingSocketThread( 6074): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6074): closeLocalSocketAndStreams: Closing the local input stream...,
D/io.jxcore.node.IncomingSocketThread( 6074): closeLocalSocketAndStreams: Closing the local output stream...,
,D/io.jxcore.node.IncomingSocketThread( 6074): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6074): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@219e57f, channel: 6, state: CONNECTED
W/io.jxcore.node.StreamCopyingThread( 6074): Either failed to read from the output stream or write to the input stream (thread ID: 1066, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6074): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6074): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/BluetoothSocket( 6074): close() this: android.bluetooth.BluetoothSocket@219e57f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@82d994c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3ce79d95mSocket: android.net.LocalSocket@36dfaeaa impl:android.net.LocalSocketImpl@5f15a9b fd:FileDescriptor[109]
D/BluetoothSocket( 6074): Closing mSocket: android.net.LocalSocket@36dfaeaa impl:android.net.LocalSocketImpl@5f15a9b fd:FileDescriptor[109]
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@219e57f, channel: 6, state: CLOSED
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@219e57f, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6074): Exiting thread (ID: 1067, name: Receiver)
D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6074): Exiting thread (ID: 1066, name: Sender)
I/jxcore-log( 6074): 2015-12-23T02:16:24.412Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6074): 
W/bt-rfcomm( 2656): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 2656): RFCOMM_DisconnectInd LCID:0x45
,D/btif_config_util( 2656): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 2656): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.CLASS_CHANGED
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote,
I/BluetoothBondStateMachine( 2656): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2656): isSecureModeOn:false
,I/BluetoothBondStateMachine( 2656): Entering PendingCommandState State
E/bt-btif ( 2656): check_cod: remote_cod = 0x5a020c
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive,
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1178):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1318): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5895): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5895): BluetoothHeadset service is binded
D/GMFPReceiver( 5895): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5895): jangil::setProperties()
,D/GMFPReceiver( 5895): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5895): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5895): ::::::::Wearable0002::false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/GMFPReceiver( 5895): onServiceConnected() : 1
D/GMFPReceiver( 5895): mBluetoothHeadset = true
,D/btif_config_util( 2656): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2656): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2656): Failed to remove device: 7C:F9:0E:51:18:22
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive,
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit,
I/BluetoothBondStateMachine( 2656): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2656): isSecureModeOn:false
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.BOND_STATE_CHANGED,
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
,D/BluetoothNotiBroadcastReceiver( 1318): onReceive
,D/HidService( 2656): getHidService(): returning com.android.bluetooth.hid.HidService@d3e2aa3
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,D/BluetoothTile( 1178):  handleUpdatestate:false name:null
,E/BluetoothHeadset( 5895): BTStateChangeCB is registed
,D/SettingsProvider( 1017): name = bluetooth_input_device_priority_7C:F9:0E:51:18:22
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/HidService( 2656): Saved priority 7C:F9:0E:51:18:22 = -1
,D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_7C:F9:0E:51:18:22
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
D/SettingsProvider( 1017): name = bluetooth_headset_priority_7C:F9:0E:51:18:22
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
I/BluetoothBondStateMachine( 2656): StableState(): Entering Off State
E/BluetoothHeadset( 5895): BluetoothHeadset service is binded
D/GMFPReceiver( 5895): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5895): jangil::setProperties()
,D/GMFPReceiver( 5895): jangil::printBTStatus()
D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5895): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5895): ::::::::Wearable0002::false
,D/GMFPReceiver( 5895): onServiceConnected() : 1
D/GMFPReceiver( 5895): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,W/bt-btif ( 2656): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2656): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2656): bta_dm_pm_ssr:2, lat:1200
,D/BluetoothSocket( 6074): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@40fe38
,E/BluetoothRemoteDevices( 2656): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Incoming connection initialized (thread ID: 1068)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6074): Entering thread (ID: 1068)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): onBytesRead: Read 83 bytes successfully (thread ID: 1068)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): onBytesWritten: 83 bytes successfully written (thread ID: 1068)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): removeThreadFromList: Removing thread with ID 1068
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Handshake thread disposed (thread ID: 1068)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
I/io.jxcore.node.ConnectionHelper( 6074): onConnected: Incoming connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
,D/io.jxcore.node.ConnectionHelper( 6074): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6074): onConnected: Incoming socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], created successfully
,D/io.jxcore.node.ConnectionHelper( 6074): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6074): Exiting thread (ID: 1068)
,D/io.jxcore.node.IncomingSocketThread( 6074): Entering thread (ID: 1069)
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10338
,I/io.jxcore.node.IncomingSocketThread( 6074): Local host address: localhost/127.0.0.1, port: 57401
,D/io.jxcore.node.IncomingSocketThread( 6074): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6074): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 6074): 2015-12-23T02:16:24.854Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6074): 
,I/io.jxcore.node.StreamCopyingThread( 6074): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 6074): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6074): Exiting thread (ID: 1069)
,D/io.jxcore.node.StreamCopyingThread( 6074): Entering thread (ID: 1071, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6074): Entering thread (ID: 1070, name: Sender)
,I/jxcore-log( 6074): 2015-12-23T02:16:25.688Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:25.691Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:25.763Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:25.767Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:25.771Z SendDataTCPServer.js: TCP/IP server has received 10120 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:25.775Z SendDataTCPServer.js: TCP/IP server has received 12144 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:25.811Z SendDataTCPServer.js: TCP/IP server has received 28528 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:25.815Z SendDataTCPServer.js: TCP/IP server has received 30552 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:25.818Z SendDataTCPServer.js: TCP/IP server has received 32576 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:25.850Z SendDataTCPServer.js: TCP/IP server has received 42888 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:25.899Z SendDataTCPServer.js: TCP/IP server has received 44912 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:25.930Z SendDataTCPServer.js: TCP/IP server has received 61104 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:25.935Z SendDataTCPServer.js: TCP/IP server has received 63128 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:25.970Z SendDataTCPServer.js: TCP/IP server has received 79320 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:25.976Z SendDataTCPServer.js: TCP/IP server has received 81344 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:25.979Z SendDataTCPServer.js: TCP/IP server has received 83368 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:26.010Z SendDataTCPServer.js: TCP/IP server has received 89440 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:26.074Z SendDataTCPServer.js: TCP/IP server has received 91464 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:26.078Z SendDataTCPServer.js: TCP/IP server has received 93488 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:26.110Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6074): 
,W/bt-btif ( 2656): invalid rfc slot id: 8
,W/io.jxcore.node.StreamCopyingThread( 6074): Either failed to read from the output stream or write to the input stream (thread ID: 1071, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6074): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6074): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1069
D/io.jxcore.node.IncomingSocketThread( 6074): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 6074): doStop: Thread ID: 1071
,D/io.jxcore.node.IncomingSocketThread( 6074): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 6074): doStop: Thread ID: 1070
D/io.jxcore.node.IncomingSocketThread( 6074): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.IncomingSocketThread( 6074): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6074): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread( 6074): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6074): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@717e11, channel: 6, state: CONNECTED
D/BluetoothSocket( 6074): close() this: android.bluetooth.BluetoothSocket@717e11, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16e20b76, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@31010577mSocket: android.net.LocalSocket@1e23c5e4 impl:android.net.LocalSocketImpl@2ddeea4d fd:FileDescriptor[109]
D/BluetoothSocket( 6074): Closing mSocket: android.net.LocalSocket@1e23c5e4 impl:android.net.LocalSocketImpl@2ddeea4d fd:FileDescriptor[109]
,D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@717e11, channel: 6, state: CLOSED
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@717e11, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6074): Exiting thread (ID: 1071, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 6074): Either failed to read from the output stream or write to the input stream (thread ID: 1070, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6074): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6074): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6074): Exiting thread (ID: 1070, name: Sender)
,I/jxcore-log( 6074): 2015-12-23T02:16:26.154Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6074): 
,W/bt-rfcomm( 2656): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
,W/bt-rfcomm( 2656): RFCOMM_DisconnectInd LCID:0x47
,E/SMD     (  292): DCD OFF
,E/bt-btm  ( 2656): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2656): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1178): Received android.bluetooth.device.action.ACL_DISCONNECTED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1318): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 1178): isGear1: device is not B1!
,D/BluetoothAdapterService( 2656): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cc83399
,D/BtConfig.SecureMode( 2656): isSecureModeOn:false
,D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2656): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5951): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5951): Bluetooth Device Name: G3-1
,E/bt-btm  ( 2656): Reset sec_bd_name and name flag. (BR/EDR link)
E/bt-btm  ( 2656): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1178): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1318): ACTION_ACL_DISCONNECTED
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2656): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cc83399
,D/BtConfig.SecureMode( 2656): isSecureModeOn:false
,D/KeyguardViewMediator( 1178): isGear1: device is not B1!
D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/BluetoothPbapService( 2656): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5951): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5951): Bluetooth Device Name: Thali Test (Galaxy A5)
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): setState: RESTARTING
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/wpa_supplicant( 1399): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1017): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): Start timer timeout, starting now...
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1399): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1017): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,E/SMD     (  292): DCD OFF
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): InactiveState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): restart: Restarting...
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/WifiP2pManager( 6074): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service request added successfully
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/WifiP2pService( 1017): InactiveState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): InactiveState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 },
D/WifiP2pService( 1017): P2pEnabledState discover services
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13],
I/wpa_supplicant( 1399): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service discovery started successfully
,E/SMD     (  292): DCD OFF
,D/IOP_DB_BT( 2656): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2656): db_query_execute: result 1
,D/IOP_DB_BT( 2656): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 2656): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2656): db_query_execute: result 1
W/bt-btif ( 2656): info:x10,
D/        ( 2656): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
E/BluetoothRemoteDevices( 2656): aclStateChangeCallback: Device is NULL
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.NAME_CHANGED
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 2656): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.CLASS_CHANGED
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2656): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 2656): isSecureModeOn:false
I/BluetoothBondStateMachine( 2656): Entering PendingCommandState State
E/bt-btif ( 2656): check_cod: remote_cod = 0x5a020c
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:,
D/BluetoothTile( 1178):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1318): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5895): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5895): BluetoothHeadset service is binded
,D/GMFPReceiver( 5895): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5895): jangil::setProperties()
,D/GMFPReceiver( 5895): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5895): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5895): ::::::::Wearable0002::false
,D/GMFPReceiver( 5895): onServiceConnected() : 1
D/GMFPReceiver( 5895): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/btif_config_util( 2656): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6438","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 6074): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438] is available
,I/jxcore-log( 6074): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT6438","peerAvailable":true}],
I/jxcore-log( 6074): 
I/jxcore-log( 6074): Found peer : LGE-LG-D722_PT6438, Available: true
I/jxcore-log( 6074): 
I/jxcore-log( 6074): startWithNextDevice
I/jxcore-log( 6074): 
I/jxcore-log( 6074): device[2]: F8:95:C7:87:85:54
I/jxcore-log( 6074): 
I/jxcore-log( 6074): 2015-12-23T02:16:45.279Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 6074): 
I/jxcore-log( 6074): 2015-12-23T02:16:45.280Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 6074): 
I/jxcore-log( 6074): 2015-12-23T02:16:45.280Z SendDataConnector.js: do connect now
I/jxcore-log( 6074): 
,I/io.jxcore.node.ConnectionHelper( 6074): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 6074): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 6074): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 1072)
,D/BluetoothUtils( 6074): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 6074): getBluetoothService() called with no BluetoothManagerCallback
,I/BluetoothBondStateMachine( 2656): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
D/BluetoothAdapterProperties( 2656): Failed to remove device: F8:95:C7:87:3C:51
,D/BTIF_SOCK( 2656): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/BluetoothSocket( 6074): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote,
,I/BluetoothBondStateMachine( 2656): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 2656): isSecureModeOn:false
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
D/HidService( 2656): getHidService(): returning com.android.bluetooth.hid.HidService@d3e2aa3
D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.BOND_STATE_CHANGED
D/SettingsProvider( 1017): name = bluetooth_input_device_priority_F8:95:C7:87:3C:51
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002,
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/BluetoothTile( 1178):  handleUpdatestate:false name:null
D/SettingsProvider( 1017): ret = -1
D/HidService( 2656): Saved priority F8:95:C7:87:3C:51 = -1
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_F8:95:C7:87:3C:51
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/SettingsProvider( 1017): name = bluetooth_headset_priority_F8:95:C7:87:3C:51
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
I/BluetoothBondStateMachine( 2656): StableState(): Entering Off State
,D/BluetoothNotiBroadcastReceiver( 1318): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5895): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5895): BluetoothHeadset service is binded
D/GMFPReceiver( 5895): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5895): jangil::setProperties()
,D/GMFPReceiver( 5895): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5895): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5895): ::::::::Wearable0002::false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
D/GMFPReceiver( 5895): onServiceConnected() : 1
D/GMFPReceiver( 5895): mBluetoothHeadset = true
,D/IOP_DB_BT( 2656): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54
,D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_VER, value 6:16653
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 2656): db_query_execute: result 1
,E/bt-btm  ( 2656): tBTM_SEC_DEV:0xa46b1d40 rs_disc_pending=1,
W/bt-btif ( 2656): bta_dm_check_av:0
,W/bt-btif ( 2656): btif_dm_cback : unhandled event (14),
,W/bt-btif ( 2656): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2656): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2656): bta_dm_pm_ssr:2, lat:1200
D/BluetoothSocket( 6074): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@37db6902
,E/BluetoothRemoteDevices( 2656): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Incoming connection initialized (thread ID: 1073)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6074): Entering thread (ID: 1073)
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): onBytesRead: Read 77 bytes successfully (thread ID: 1073)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): onBytesWritten: 83 bytes successfully written (thread ID: 1073)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): removeThreadFromList: Removing thread with ID 1073
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Handshake thread disposed (thread ID: 1073)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6074): Exiting thread (ID: 1073)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,I/io.jxcore.node.ConnectionHelper( 6074): onConnected: Incoming connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/io.jxcore.node.ConnectionHelper( 6074): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6074): onConnected: Incoming socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], created successfully
D/io.jxcore.node.ConnectionHelper( 6074): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 6074): Entering thread (ID: 1074),
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10338
,I/jxcore-log( 6074): 2015-12-23T02:16:46.188Z SendDataTCPServer.js: TCP/IP server connected,
I/jxcore-log( 6074): 
I/io.jxcore.node.IncomingSocketThread( 6074): Local host address: localhost/127.0.0.1, port: 57401
,D/io.jxcore.node.IncomingSocketThread( 6074): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6074): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6074): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6074): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 6074): Exiting thread (ID: 1074)
,D/io.jxcore.node.StreamCopyingThread( 6074): Entering thread (ID: 1075, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 6074): Entering thread (ID: 1076, name: Receiver)
,D/IOP_DB_BT( 2656): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_VER, value 6:16653
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2656): db_query_execute: result 1
W/bt-btif ( 2656): info:x10
D/        ( 2656): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2656): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.NAME_CHANGED
,W/bt-sdp  ( 2656): process_service_search_attr_rsp
,I/jxcore-log( 6074): 2015-12-23T02:16:46.859Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:46.863Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:46.868Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:46.905Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:46.911Z SendDataTCPServer.js: TCP/IP server has received 10120 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:46.916Z SendDataTCPServer.js: TCP/IP server has received 12144 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:46.950Z SendDataTCPServer.js: TCP/IP server has received 16192 bytes of data
I/jxcore-log( 6074): 
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 2656): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,I/jxcore-log( 6074): 2015-12-23T02:16:46.996Z SendDataTCPServer.js: TCP/IP server has received 18216 bytes of data
I/jxcore-log( 6074): 
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.CLASS_CHANGED
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2656): check_cod: remote_cod = 0x5a020c,
I/jxcore-log( 6074): 2015-12-23T02:16:47.002Z SendDataTCPServer.js: TCP/IP server has received 20240 bytes of data
I/jxcore-log( 6074): 
I/BluetoothBondStateMachine( 2656): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2656): isSecureModeOn:false
I/BluetoothBondStateMachine( 2656): Entering PendingCommandState State,
,I/jxcore-log( 6074): 2015-12-23T02:16:47.007Z SendDataTCPServer.js: TCP/IP server has received 22264 bytes of data
I/jxcore-log( 6074): 
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1178):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1318): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5895): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5895): BluetoothHeadset service is binded
D/GMFPReceiver( 5895): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5895): jangil::setProperties()
,D/GMFPReceiver( 5895): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5895): ::::::::Wearable0001::false
,I/jxcore-log( 6074): 2015-12-23T02:16:47.041Z SendDataTCPServer.js: TCP/IP server has received 28336 bytes of data
I/jxcore-log( 6074): 
,D/SettingsProvider( 1017): name = Wearable0002
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5895): ::::::::Wearable0002::false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/GMFPReceiver( 5895): onServiceConnected() : 1
D/GMFPReceiver( 5895): mBluetoothHeadset = true
,I/jxcore-log( 6074): 2015-12-23T02:16:47.089Z SendDataTCPServer.js: TCP/IP server has received 30360 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:47.093Z SendDataTCPServer.js: TCP/IP server has received 32384 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:47.130Z SendDataTCPServer.js: TCP/IP server has received 36432 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:47.168Z SendDataTCPServer.js: TCP/IP server has received 38456 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:47.172Z SendDataTCPServer.js: TCP/IP server has received 40480 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:47.207Z SendDataTCPServer.js: TCP/IP server has received 42504 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:47.241Z SendDataTCPServer.js: TCP/IP server has received 52624 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:47.243Z SendDataTCPServer.js: TCP/IP server has received 54648 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:47.266Z SendDataTCPServer.js: TCP/IP server has received 56672 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:47.301Z SendDataTCPServer.js: TCP/IP server has received 70840 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:47.305Z SendDataTCPServer.js: TCP/IP server has received 72864 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:47.309Z SendDataTCPServer.js: TCP/IP server has received 74888 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:47.341Z SendDataTCPServer.js: TCP/IP server has received 80960 bytes of data,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:47.359Z SendDataTCPServer.js: TCP/IP server has received 82984 bytes of data
I/jxcore-log( 6074): 
,D/btif_config_util( 2656): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
I/jxcore-log( 6074): 2015-12-23T02:16:47.392Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:47.400Z SendDataTCPServer.js: TCP/IP server has received 93104 bytes of data,
I/jxcore-log( 6074): 
,I/BluetoothBondStateMachine( 2656): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2656): Failed to remove device: F8:95:C7:87:85:54
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2656): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2656): isSecureModeOn:false
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
,D/HidService( 2656): getHidService(): returning com.android.bluetooth.hid.HidService@d3e2aa3
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/SettingsProvider( 1017): name = bluetooth_input_device_priority_F8:95:C7:87:85:54
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/HidService( 2656): Saved priority F8:95:C7:87:85:54 = -1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
I/jxcore-log( 6074): 2015-12-23T02:16:47.443Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6074): 
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_F8:95:C7:87:85:54
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/BluetoothTile( 1178):  handleUpdatestate:false name:null
,D/SettingsProvider( 1017): name = bluetooth_headset_priority_F8:95:C7:87:85:54
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,I/BluetoothBondStateMachine( 2656): StableState(): Entering Off State
,D/BluetoothNotiBroadcastReceiver( 1318): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5895): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5895): BluetoothHeadset service is binded
D/GMFPReceiver( 5895): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5895): jangil::setProperties()
,D/GMFPReceiver( 5895): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5895): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5895): ::::::::Wearable0002::false
,D/GMFPReceiver( 5895): onServiceConnected() : 1
D/GMFPReceiver( 5895): mBluetoothHeadset = true
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,E/bt-btm  ( 2656): tBTM_SEC_DEV:0xa46b1d40 rs_disc_pending=0
,W/bt-btif ( 2656): bta_dm_check_av:0
,W/bt-btif ( 2656): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2656): invalid rfc slot id: 9
,W/io.jxcore.node.StreamCopyingThread( 6074): Either failed to read from the output stream or write to the input stream (thread ID: 1076, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6074): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 6074): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1074
,D/io.jxcore.node.IncomingSocketThread( 6074): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6074): doStop: Thread ID: 1076
D/io.jxcore.node.IncomingSocketThread( 6074): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 6074): doStop: Thread ID: 1075
D/io.jxcore.node.IncomingSocketThread( 6074): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.IncomingSocketThread( 6074): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6074): Either failed to read from the output stream or write to the input stream (thread ID: 1075, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6074): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6074): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 6074): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread( 6074): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6074): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@1bf68213, channel: 6, state: CONNECTED
,D/BluetoothSocket( 6074): close() this: android.bluetooth.BluetoothSocket@1bf68213, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31495c50, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@c3cde49mSocket: android.net.LocalSocket@371b134e impl:android.net.LocalSocketImpl@32bd2c6f fd:FileDescriptor[109]
D/BluetoothSocket( 6074): Closing mSocket: android.net.LocalSocket@371b134e impl:android.net.LocalSocketImpl@32bd2c6f fd:FileDescriptor[109]
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@1bf68213, channel: 6, state: CLOSED
,D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@1bf68213, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6074): Exiting thread (ID: 1076, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6074): Exiting thread (ID: 1075, name: Sender)
,I/jxcore-log( 6074): 2015-12-23T02:16:47.768Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6074): 
,E/SMD     (  292): DCD OFF
,E/bt-btm  ( 2656): tBTM_SEC_DEV:0xa46b1d40 rs_disc_pending=1,
W/bt-btif ( 2656): bta_dm_check_av:0
,W/bt-btif ( 2656): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2656): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
,W/bt-rfcomm( 2656): RFCOMM_DisconnectInd LCID:0x4a
,E/bt-btm  ( 2656): tBTM_SEC_DEV:0xa46b1f04 rs_disc_pending=0
,W/bt-btif ( 2656): bta_dm_check_av:0
W/bt-btif ( 2656): btif_dm_cback : unhandled event (14)
,W/bt-l2cap( 2656): L2CAP - no CCB for conn rsp, LCID: 76 RCID: 69
,W/bt-btif ( 2656): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2656): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2656): bta_dm_pm_ssr:2, lat:1200
,D/BluetoothSocket( 6074): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@aefed7c
,E/BluetoothRemoteDevices( 2656): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Incoming connection initialized (thread ID: 1077)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6074): Entering thread (ID: 1077)
,E/bt-btm  ( 2656): tBTM_SEC_DEV:0xa46b1d40 rs_disc_pending=1
,W/bt-btif ( 2656): bta_dm_check_av:0
,W/bt-btif ( 2656): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2656): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2656): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2656): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2656): bta_dm_pm_ssr:2, lat:1200
E/BluetoothRemoteDevices( 2656): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): onSocketConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1072)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): onBytesWritten: 83 bytes successfully written (thread ID: 1078)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): Outgoing connection initialized (*handshake* thread ID: 1078)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): Exiting thread (thread ID: 1072)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6074): Entering thread (ID: 1078)
,E/bt-btm  ( 2656): tBTM_SEC_DEV:0xa46b1f04 rs_disc_pending=1
,W/bt-btif ( 2656): bta_dm_check_av:0
,W/bt-btif ( 2656): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): onBytesRead: Read 77 bytes successfully (thread ID: 1077)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): onBytesWritten: 83 bytes successfully written (thread ID: 1077)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): removeThreadFromList: Removing thread with ID 1077
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Handshake thread disposed (thread ID: 1077)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6074): Exiting thread (ID: 1077)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
I/io.jxcore.node.ConnectionHelper( 6074): onConnected: Incoming connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/io.jxcore.node.ConnectionHelper( 6074): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
,W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6074): onConnected: Incoming socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], created successfully
,D/io.jxcore.node.ConnectionHelper( 6074): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 6074): Entering thread (ID: 1079)
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10338
,I/io.jxcore.node.IncomingSocketThread( 6074): Local host address: localhost/127.0.0.1, port: 57401
,D/io.jxcore.node.IncomingSocketThread( 6074): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6074): setBufferSize: Setting buffer size to 8192 bytes,
I/io.jxcore.node.StreamCopyingThread( 6074): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6074): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6074): Exiting thread (ID: 1079)
I/jxcore-log( 6074): 2015-12-23T02:16:50.240Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6074): 
D/io.jxcore.node.StreamCopyingThread( 6074): Entering thread (ID: 1081, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6074): Entering thread (ID: 1080, name: Sender)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): onBytesRead: Read 77 bytes successfully (thread ID: 1078)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): Handshake succeeded with [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): onHandshakeSucceeded: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438],
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6074): Exiting thread (ID: 1078),
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
I/io.jxcore.node.ConnectionHelper( 6074): onConnected: Outgoing connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
,D/io.jxcore.node.ConnectionHelper( 6074): hasConnection: We have an incoming connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 6074): onConnected: Already connected with peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6074): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6074): onConnected: The total number of connections is now 2
D/io.jxcore.node.OutgoingSocketThread( 6074): Entering thread (ID: 1082)
,D/io.jxcore.node.OutgoingSocketThread( 6074): Server socket local port: 35208
I/io.jxcore.node.OutgoingSocketThread( 6074): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 6074): onListeningForIncomingConnections: Outgoing connection is using port 35208 (peer ID: F8:95:C7:87:85:54)
,I/jxcore-log( 6074): 2015-12-23T02:16:50.555Z SendDataConnector.js: CLIENT connected to 35208, error: null
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:50.556Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6074): 
,I/io.jxcore.node.OutgoingSocketThread( 6074): Incoming data from address: /127.0.0.1, port: 35208
D/io.jxcore.node.OutgoingSocketThread( 6074): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6074): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6074): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 6074): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6074): Exiting thread (ID: 1082)
,D/io.jxcore.node.StreamCopyingThread( 6074): Entering thread (ID: 1084, name: Receiver)
I/jxcore-log( 6074): 2015-12-23T02:16:50.562Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6074): 
D/io.jxcore.node.StreamCopyingThread( 6074): Entering thread (ID: 1083, name: Sender)
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/bt-btm  ( 2656): tBTM_SEC_DEV:0xa46b1d40 rs_disc_pending=1,
,W/bt-btif ( 2656): bta_dm_check_av:0
W/bt-btif ( 2656): btif_dm_cback : unhandled event (14)
,E/SMD     (  292): DCD OFF,
,I/jxcore-log( 6074): 2015-12-23T02:16:51.458Z SendDataTCPServer.js: TCP/IP server has received 2024 bytes of data,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:51.463Z SendDataTCPServer.js: TCP/IP server has received 4048 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:51.490Z SendDataTCPServer.js: TCP/IP server has received 6072 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:51.541Z SendDataTCPServer.js: TCP/IP server has received 8096 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:51.566Z SendDataTCPServer.js: TCP/IP server has received 10120 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:51.631Z SendDataTCPServer.js: TCP/IP server has received 12144 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:51.670Z SendDataTCPServer.js: TCP/IP server has received 14168 bytes of data,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:51.685Z SendDataTCPServer.js: TCP/IP server has received 16192 bytes of data,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:51.715Z SendDataTCPServer.js: TCP/IP server has received 18216 bytes of data,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:51.740Z SendDataTCPServer.js: TCP/IP server has received 20240 bytes of data,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:51.747Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:51.761Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:51.765Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:51.769Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:51.793Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:51.796Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:51.845Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:51.849Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:51.923Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:51.979Z SendDataTCPServer.js: TCP/IP server has received 22264 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:52.010Z SendDataTCPServer.js: TCP/IP server has received 24288 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:52.027Z SendDataTCPServer.js: TCP/IP server has received 26312 bytes of data
I/jxcore-log( 6074): 
,E/bt-btm  ( 2656): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2656): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1178): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/Watchdog( 1017): !@Sync 21
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive,
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.ACL_DISCONNECTED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/jxcore-log( 6074): 2015-12-23T02:16:52.108Z SendDataTCPServer.js: TCP/IP server has received 28336 bytes of data
I/jxcore-log( 6074): 
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,E/BluetoothEventManager( 1318): ACTION_ACL_DISCONNECTED
,I/jxcore-log( 6074): 2015-12-23T02:16:52.114Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:52.114Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6074): 
I/jxcore-log( 6074): oneRoundDownNow
I/jxcore-log( 6074): 
I/jxcore-log( 6074): 2015-12-23T02:16:52.115Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:52.115Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6074): 
,D/io.jxcore.node.ConnectionHelper( 6074): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
I/io.jxcore.node.OutgoingSocketThread( 6074): close
D/io.jxcore.node.OutgoingSocketThread( 6074): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6074): doStop: Thread ID: 1084
D/io.jxcore.node.OutgoingSocketThread( 6074): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6074): doStop: Thread ID: 1083
D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6074): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@2c6c1605, channel: 8, state: CONNECTED
D/BluetoothSocket( 6074): close() this: android.bluetooth.BluetoothSocket@2c6c1605, channel: 8, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2599165a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@a9a208bmSocket: android.net.LocalSocket@300c6568 impl:android.net.LocalSocketImpl@129d0d81 fd:FileDescriptor[111]
D/BluetoothSocket( 6074): Closing mSocket: android.net.LocalSocket@300c6568 impl:android.net.LocalSocketImpl@129d0d81 fd:FileDescriptor[111]
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@2c6c1605, channel: 8, state: CLOSED
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@2c6c1605, channel: 8, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6074): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:85:54
,I/jxcore-log( 6074): 2015-12-23T02:16:52.120Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 6074): 
W/io.jxcore.node.StreamCopyingThread( 6074): Either failed to read from the output stream or write to the input stream (thread ID: 1084, thread name: Receiver): bt socket closed, read return: -1
W/io.jxcore.node.StreamCopyingThread( 6074): Either failed to read from the output stream or write to the input stream (thread ID: 1083, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6074): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6074): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6074): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 6074): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
E/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6074): Exiting thread (ID: 1084, name: Receiver)
I/jxcore-log( 6074): ---- round done--------
I/jxcore-log( 6074): 
I/jxcore-log( 6074): startWithNextDevice
I/jxcore-log( 6074): 
E/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6074): Exiting thread (ID: 1083, name: Sender)
I/jxcore-log( 6074): 2015-12-23T02:16:52.124Z SendDataTCPServer.js: TCP/IP server has received 32384 bytes of data
I/jxcore-log( 6074): 
D/KeyguardViewMediator( 1178): isGear1: device is not B1!
,D/BluetoothAdapterService( 2656): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cc83399
,D/BtConfig.SecureMode( 2656): isSecureModeOn:false
,D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/jxcore-log( 6074): 2015-12-23T02:16:52.130Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 6074): 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2656): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5951): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5951): Bluetooth Device Name: G4-1
,I/jxcore-log( 6074): 2015-12-23T02:16:52.170Z SendDataTCPServer.js: TCP/IP server has received 44912 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:52.180Z SendDataTCPServer.js: TCP/IP server has received 46936 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:52.210Z SendDataTCPServer.js: TCP/IP server has received 48960 bytes of data
I/jxcore-log( 6074): 
,W/bt-btif ( 2656): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,I/jxcore-log( 6074): 2015-12-23T02:16:52.251Z SendDataTCPServer.js: TCP/IP server has received 50984 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:52.255Z SendDataTCPServer.js: TCP/IP server has received 53008 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:52.290Z SendDataTCPServer.js: TCP/IP server has received 63128 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:52.342Z SendDataTCPServer.js: TCP/IP server has received 65152 bytes of data
I/jxcore-log( 6074): 
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): restart: Restarting...
D/WifiP2pService( 1017): InactiveState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState clear service request
,I/jxcore-log( 6074): 2015-12-23T02:16:52.380Z SendDataTCPServer.js: TCP/IP server has received 69200 bytes of data
I/jxcore-log( 6074): 
,D/WifiP2pService( 1017): InactiveState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pManager( 6074): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service request added successfully
,I/jxcore-log( 6074): 2015-12-23T02:16:52.422Z SendDataTCPServer.js: TCP/IP server has received 71224 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:52.427Z SendDataTCPServer.js: TCP/IP server has received 73248 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:52.460Z SendDataTCPServer.js: TCP/IP server has received 79320 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:52.511Z SendDataTCPServer.js: TCP/IP server has received 81344 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:52.515Z SendDataTCPServer.js: TCP/IP server has received 83368 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:52.550Z SendDataTCPServer.js: TCP/IP server has received 87416 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:52.613Z SendDataTCPServer.js: TCP/IP server has received 89440 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:52.618Z SendDataTCPServer.js: TCP/IP server has received 91464 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:52.690Z SendDataTCPServer.js: TCP/IP server has received 93488 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:52.730Z SendDataTCPServer.js: TCP/IP server has received 99560 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:16:52.974Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6074): 
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1399): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service discovery started successfully
,W/io.jxcore.node.StreamCopyingThread( 6074): Either failed to read from the output stream or write to the input stream (thread ID: 1081, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6074): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6074): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1079
D/io.jxcore.node.OutgoingSocketThread( 6074): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6074): doStop: Thread ID: 1081,
,D/io.jxcore.node.OutgoingSocketThread( 6074): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6074): doStop: Thread ID: 1080
D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6074): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@39c23e26, channel: 6, state: CONNECTED
D/BluetoothSocket( 6074): close() this: android.bluetooth.BluetoothSocket@39c23e26, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e083a67, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3df67014mSocket: android.net.LocalSocket@3b8c00bd impl:android.net.LocalSocketImpl@120416b2 fd:FileDescriptor[109]
D/BluetoothSocket( 6074): Closing mSocket: android.net.LocalSocket@3b8c00bd impl:android.net.LocalSocketImpl@120416b2 fd:FileDescriptor[109]
,D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@39c23e26, channel: 6, state: CLOSED
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@39c23e26, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6074): Exiting thread (ID: 1081, name: Receiver)
W/bt-btif ( 2656): invalid rfc slot id: 11
W/io.jxcore.node.StreamCopyingThread( 6074): Either failed to read from the output stream or write to the input stream (thread ID: 1080, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6074): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6074): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6074): Exiting thread (ID: 1080, name: Sender)
I/jxcore-log( 6074): 2015-12-23T02:16:53.474Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6074): 
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7855","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911],
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911] already in the list, will not add again
,W/bt-rfcomm( 2656): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 2656): RFCOMM_DisconnectInd LCID:0x4d
,E/SMD     (  292): DCD OFF
,E/bt-btm  ( 2656): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2656): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1178): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1318): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/KeyguardViewMediator( 1178): isGear1: device is not B1!
,D/BluetoothAdapterService( 2656): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cc83399
,D/BtConfig.SecureMode( 2656): isSecureModeOn:false
,D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2656): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5951): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5951): Bluetooth Device Name: G3s-1
,D/IOP_DB_BT( 2656): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69,
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 2656): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2656): db_query_execute: result 1
,D/IOP_DB_BT( 2656): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2656): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2656): db_query_execute: result 1
,W/bt-btif ( 2656): info:x10
,D/        ( 2656): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2656): aclStateChangeCallback: Device is NULL
,E/SMD     (  292): DCD OFF
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.NAME_CHANGED
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 },
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,I/BluetoothBondStateMachine( 2656): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1,
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.NAME_CHANGED,
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.CLASS_CHANGED
,E/bt-btif ( 2656): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2656): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11,
D/BtConfig.SecureMode( 2656): isSecureModeOn:false
,I/BluetoothBondStateMachine( 2656): Entering PendingCommandState State
,D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1178):  handleUpdatestate:false name:null
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothNotiBroadcastReceiver( 1318): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5895): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5895): BluetoothHeadset service is binded
D/GMFPReceiver( 5895): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5895): jangil::setProperties()
,D/GMFPReceiver( 5895): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5895): ::::::::Wearable0001::false,
D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5895): ::::::::Wearable0002::false
,D/GMFPReceiver( 5895): onServiceConnected() : 1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/GMFPReceiver( 5895): mBluetoothHeadset = true
,D/btif_config_util( 2656): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2656): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2656): Failed to remove device: B0:C5:59:3F:75:69
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
I/BluetoothBondStateMachine( 2656): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2656): isSecureModeOn:false
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.BOND_STATE_CHANGED
D/HidService( 2656): getHidService(): returning com.android.bluetooth.hid.HidService@d3e2aa3
D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
,D/SettingsProvider( 1017): name = bluetooth_input_device_priority_B0:C5:59:3F:75:69
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/BluetoothTile( 1178):  handleUpdatestate:false name:null
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
D/HidService( 2656): Saved priority B0:C5:59:3F:75:69 = -1
D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_B0:C5:59:3F:75:69
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/SettingsProvider( 1017): name = bluetooth_headset_priority_B0:C5:59:3F:75:69
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,I/BluetoothBondStateMachine( 2656): StableState(): Entering Off State
,D/BluetoothNotiBroadcastReceiver( 1318): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5895): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5895): BluetoothHeadset service is binded,
D/GMFPReceiver( 5895): android.bluetooth.device.action.BOND_STATE_CHANGED,
D/GMFPReceiver( 5895): jangil::setProperties()
,D/GMFPReceiver( 5895): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5895): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5895): ::::::::Wearable0002::false
,D/GMFPReceiver( 5895): onServiceConnected() : 1
D/GMFPReceiver( 5895): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,W/bt-btif ( 2656): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2656): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2656): bta_dm_pm_ssr:2, lat:1200
,D/BluetoothSocket( 6074): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@2a541603
,E/BluetoothRemoteDevices( 2656): setRfcommConnected true,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Incoming connection initialized (thread ID: 1085)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6074): Entering thread (ID: 1085)
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.,
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1017): DefaultState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): restart: Restarting...
D/WifiP2pService( 1017): InactiveState{ what=139301 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pManager( 6074): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): onBytesRead: Read 82 bytes successfully (thread ID: 1085)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): onBytesWritten: 83 bytes successfully written (thread ID: 1085)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): removeThreadFromList: Removing thread with ID 1085
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Handshake thread disposed (thread ID: 1085)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6074): Exiting thread (ID: 1085)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/io.jxcore.node.ConnectionHelper( 6074): onConnected: Incoming connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/io.jxcore.node.ConnectionHelper( 6074): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
,D/io.jxcore.node.ConnectionHelper( 6074): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] is available
I/jxcore-log( 6074): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT6068","peerAvailable":true}]
I/jxcore-log( 6074): 
I/jxcore-log( 6074): Found peer : samsung-SM-G900F_PT6068, Available: true
I/jxcore-log( 6074): 
I/jxcore-log( 6074): startWithNextDevice
I/jxcore-log( 6074): 
I/jxcore-log( 6074): device[3]: B0:C5:59:3F:75:69
I/jxcore-log( 6074): 
I/jxcore-log( 6074): 2015-12-23T02:17:02.490Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:02.491Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 6074): 
I/jxcore-log( 6074): 2015-12-23T02:17:02.491Z SendDataConnector.js: do connect now
I/jxcore-log( 6074): 
,I/io.jxcore.node.ConnectionHelper( 6074): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
,D/io.jxcore.node.ConnectionHelper( 6074): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): connect: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): connect: Trying to start connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): onConnecting: Thali Test (Galaxy S5) B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): connect: Started connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 6074): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 1086)
,I/io.jxcore.node.ConnectionHelper( 6074): onConnected: Incoming socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], created successfully,
D/io.jxcore.node.ConnectionHelper( 6074): onConnected: The total number of connections is now 1
D/BluetoothUtils( 6074): isSocketAllowedBySecurityPolicy start : device null,
W/BluetoothAdapter( 6074): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2656): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/BluetoothSocket( 6074): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
,D/io.jxcore.node.IncomingSocketThread( 6074): Entering thread (ID: 1087)
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10338
,I/io.jxcore.node.IncomingSocketThread( 6074): Local host address: localhost/127.0.0.1, port: 57401
,D/io.jxcore.node.IncomingSocketThread( 6074): Setting local streams and starting stream copying threads...
,I/jxcore-log( 6074): 2015-12-23T02:17:02.516Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6074): 
,I/io.jxcore.node.StreamCopyingThread( 6074): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6074): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 6074): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 6074): Exiting thread (ID: 1087)
,D/io.jxcore.node.StreamCopyingThread( 6074): Entering thread (ID: 1089, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6074): Entering thread (ID: 1088, name: Sender)
,W/bt-sdp  ( 2656): process_service_search_attr_rsp
,E/SMD     (  292): DCD OFF
,W/bt-btif ( 2656): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2656): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2656): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2656): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2656): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): onSocketConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1086)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): onBytesWritten: 83 bytes successfully written (thread ID: 1090)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): Outgoing connection initialized (*handshake* thread ID: 1090)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): Exiting thread (thread ID: 1086)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6074): Entering thread (ID: 1090)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): onBytesRead: Read 82 bytes successfully (thread ID: 1090)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6074): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): onHandshakeSucceeded: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6074): Exiting thread (ID: 1090)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/io.jxcore.node.ConnectionHelper( 6074): onConnected: Outgoing connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
,D/io.jxcore.node.ConnectionHelper( 6074): hasConnection: We have an incoming connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 6074): onConnected: Already connected with peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6074): onConnected: Outgoing socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 6074): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 6074): Entering thread (ID: 1091)
,D/io.jxcore.node.OutgoingSocketThread( 6074): Server socket local port: 56114
I/io.jxcore.node.OutgoingSocketThread( 6074): Now accepting connections...
,D/SSRM:n  ( 1017): SIOP:: AP = 270
I/io.jxcore.node.ConnectionHelper( 6074): onListeningForIncomingConnections: Outgoing connection is using port 56114 (peer ID: B0:C5:59:3F:75:69)
,I/jxcore-log( 6074): 2015-12-23T02:17:03.331Z SendDataConnector.js: CLIENT connected to 56114, error: null
I/jxcore-log( 6074): 
I/jxcore-log( 6074): 2015-12-23T02:17:03.331Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6074): 
I/jxcore-log( 6074): 2015-12-23T02:17:03.335Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6074): 
,I/io.jxcore.node.OutgoingSocketThread( 6074): Incoming data from address: /127.0.0.1, port: 56114
D/io.jxcore.node.OutgoingSocketThread( 6074): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6074): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6074): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6074): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread( 6074): Exiting thread (ID: 1091)
,D/io.jxcore.node.StreamCopyingThread( 6074): Entering thread (ID: 1093, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6074): Entering thread (ID: 1092, name: Sender)
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1399): USE_NETWORK : USE_NETWORK OFF
I/jxcore-log( 6074): 2015-12-23T02:17:03.730Z SendDataTCPServer.js: TCP/IP server has received 22456 bytes of data
I/jxcore-log( 6074): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service discovery started successfully
,I/jxcore-log( 6074): 2015-12-23T02:17:03.762Z SendDataTCPServer.js: TCP/IP server has received 24480 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:03.814Z SendDataTCPServer.js: TCP/IP server has received 26504 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:03.821Z SendDataTCPServer.js: TCP/IP server has received 28528 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:03.840Z SendDataTCPServer.js: TCP/IP server has received 30552 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:03.890Z SendDataTCPServer.js: TCP/IP server has received 32576 bytes of data,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:03.927Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:03.993Z SendDataTCPServer.js: TCP/IP server has received 34792 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:04.000Z SendDataTCPServer.js: TCP/IP server has received 36816 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:04.053Z SendDataTCPServer.js: TCP/IP server has received 38840 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:04.060Z SendDataTCPServer.js: TCP/IP server has received 40864 bytes of data,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:04.069Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6074): 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,I/jxcore-log( 6074): 2015-12-23T02:17:04.121Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:04.239Z SendDataConnector.js: CLIENT is data received : 30000,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:04.431Z SendDataConnector.js: CLIENT is data received : 40000,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:04.555Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:04.736Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:04.796Z SendDataConnector.js: CLIENT is data received : 70000,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:04.865Z SendDataTCPServer.js: TCP/IP server has received 42888 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:04.900Z SendDataTCPServer.js: TCP/IP server has received 48960 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:04.944Z SendDataTCPServer.js: TCP/IP server has received 50984 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:04.983Z SendDataTCPServer.js: TCP/IP server has received 53008 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.020Z SendDataTCPServer.js: TCP/IP server has received 61104 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.042Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.046Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.049Z SendDataTCPServer.js: TCP/IP server has received 63128 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.080Z SendDataTCPServer.js: TCP/IP server has received 69200 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.120Z SendDataTCPServer.js: TCP/IP server has received 71224 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.125Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.126Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): oneRoundDownNow
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.127Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.128Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6074): 
,D/io.jxcore.node.ConnectionHelper( 6074): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
,I/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B0:C5:59:3F:75:69
I/io.jxcore.node.OutgoingSocketThread( 6074): close
,D/io.jxcore.node.OutgoingSocketThread( 6074): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6074): doStop: Thread ID: 1093
D/io.jxcore.node.OutgoingSocketThread( 6074): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 6074): doStop: Thread ID: 1092
D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6074): Either failed to read from the output stream or write to the input stream (thread ID: 1092, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 6074): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6074): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6074): closeBluetoothSocketAndStreams
,D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@2dd47980, channel: 6, state: CONNECTED
,D/BluetoothSocket( 6074): close() this: android.bluetooth.BluetoothSocket@2dd47980, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@397cebb9, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1418ebfemSocket: android.net.LocalSocket@2af80f5f impl:android.net.LocalSocketImpl@22c7adac fd:FileDescriptor[112]
D/BluetoothSocket( 6074): Closing mSocket: android.net.LocalSocket@2af80f5f impl:android.net.LocalSocketImpl@22c7adac fd:FileDescriptor[112]
,W/io.jxcore.node.StreamCopyingThread( 6074): Either failed to read from the output stream or write to the input stream (thread ID: 1093, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 6074): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6074): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@2dd47980, channel: 6, state: CLOSED
,D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@2dd47980, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6074): disconnectOutgoingConnection: Successfully disconnected (peer ID: B0:C5:59:3F:75:69
,E/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6074): Exiting thread (ID: 1092, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6074): Exiting thread (ID: 1093, name: Receiver)
,I/jxcore-log( 6074): 2015-12-23T02:17:05.145Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69,
I/jxcore-log( 6074): 
I/jxcore-log( 6074): ---- round done--------
I/jxcore-log( 6074): 
I/jxcore-log( 6074): startWithNextDevice
I/jxcore-log( 6074): ,
,I/jxcore-log( 6074): 2015-12-23T02:17:05.172Z SendDataTCPServer.js: TCP/IP server has received 73248 bytes of data,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.210Z SendDataTCPServer.js: TCP/IP server has received 75272 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.285Z SendDataTCPServer.js: TCP/IP server has received 77296 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.289Z SendDataTCPServer.js: TCP/IP server has received 79320 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.292Z SendDataTCPServer.js: TCP/IP server has received 81344 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.296Z SendDataTCPServer.js: TCP/IP server has received 83368 bytes of data
I/jxcore-log( 6074): 
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4998","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1017): P2pEnabledState receive service response
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] already in the list, will not add again
,I/jxcore-log( 6074): 2015-12-23T02:17:05.353Z SendDataTCPServer.js: TCP/IP server has received 85392 bytes of data,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.360Z SendDataTCPServer.js: TCP/IP server has received 87416 bytes of data
I/jxcore-log( 6074): 
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7855","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] already in the list, will not add again
,I/jxcore-log( 6074): 2015-12-23T02:17:05.465Z SendDataTCPServer.js: TCP/IP server has received 89440 bytes of data,
I/jxcore-log( 6074): 
,W/bt-btif ( 2656): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND,
I/jxcore-log( 6074): 2015-12-23T02:17:05.469Z SendDataTCPServer.js: TCP/IP server has received 91464 bytes of data
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.477Z SendDataTCPServer.js: TCP/IP server has received 93488 bytes of data,
I/jxcore-log( 6074): 
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6068","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] already in the list, will not add again
,I/jxcore-log( 6074): 2015-12-23T02:17:05.527Z SendDataTCPServer.js: TCP/IP server has received 95512 bytes of data,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.531Z SendDataTCPServer.js: TCP/IP server has received 97536 bytes of data,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.534Z SendDataTCPServer.js: TCP/IP server has received 99560 bytes of data,
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:05.536Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6074): 
,E/SMD     (  292): DCD OFF
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3911","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911] already in the list, will not add again
,W/bt-btif ( 2656): invalid rfc slot id: 12
,W/io.jxcore.node.StreamCopyingThread( 6074): Either failed to read from the output stream or write to the input stream (thread ID: 1089, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6074): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6074): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1087
D/io.jxcore.node.OutgoingSocketThread( 6074): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6074): doStop: Thread ID: 1089
D/io.jxcore.node.OutgoingSocketThread( 6074): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6074): doStop: Thread ID: 1088
D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6074): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6074): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@24f78a75, channel: 6, state: CONNECTED
D/BluetoothSocket( 6074): close() this: android.bluetooth.BluetoothSocket@24f78a75, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3513ca0a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2eb8427bmSocket: android.net.LocalSocket@2ed7f898 impl:android.net.LocalSocketImpl@1d4358f1 fd:FileDescriptor[109]
D/BluetoothSocket( 6074): Closing mSocket: android.net.LocalSocket@2ed7f898 impl:android.net.LocalSocketImpl@1d4358f1 fd:FileDescriptor[109]
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@24f78a75, channel: 6, state: CLOSED
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@24f78a75, channel: 6, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6074): Exiting thread (ID: 1089, name: Receiver)
W/io.jxcore.node.StreamCopyingThread( 6074): Either failed to read from the output stream or write to the input stream (thread ID: 1088, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6074): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6074): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6074): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6074): Exiting thread (ID: 1088, name: Sender)
,I/jxcore-log( 6074): 2015-12-23T02:17:05.840Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6074): 
,W/bt-rfcomm( 2656): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
,W/bt-rfcomm( 2656): RFCOMM_DisconnectInd LCID:0x4f
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
,I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6545","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545] already in the list, will not add again
,E/SMD     (  292): DCD OFF
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): InactiveState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6545]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3911], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3911]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,E/bt-btm  ( 2656): Reset sec_bd_name and name flag. (BR/EDR link),
E/bt-btm  ( 2656): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1178): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1318): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1318): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2656): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2cc83399
D/KeyguardViewMediator( 1178): isGear1: device is not B1!
,D/BtConfig.SecureMode( 2656): isSecureModeOn:false
,D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2656): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 5951): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 5951): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): restart: Restarting...
,D/WifiP2pService( 1017): InactiveState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pManager( 6074): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service request added successfully
,D/SSRM:n  ( 1017): SIOP:: AP = 270,
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true,
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13],
I/wpa_supplicant( 1399): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1399): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service discovery started successfully
,I/wpa_supplicant( 1399): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1399): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT4998","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
,D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
,W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7855","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/WifiP2pService( 1017): P2pEnabledState receive service response
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] already in the list, will not add again
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 22
,I/PowerManagerService( 1017): [PWL] Off : 600s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,I/jxcore-log( 6074): timeout now
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): weAreDoneNow, resultArray.length: 3
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): sendReportNow
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): done, now sending data to server
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:37.110Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6074): 
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): setState: RESTARTING
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
I/wpa_supplicant( 1399): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1017): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
I/MotionRecognitionService( 1017): mGripSensorEnabled= false,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2656): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2656): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): Start timer timeout, starting now...
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1399): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): P2P device discovery started successfully,
D/WifiP2pService( 1017): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,E/SMD     (  292): DCD OFF
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT4998], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4998],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): restart: Restarting...
,D/WifiP2pService( 1017): InactiveState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pManager( 6074): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service request added successfully
,D/WifiP2pService( 1017): InactiveState{ what=139310 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139310 },
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true,
D/WifiP2pService( 1017): P2pEnabledState discover services
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1399): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service discovery started successfully,
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT7855","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/WifiP2pService( 1017): P2pEnabledState receive service response
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 },
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnector,lib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855], add/update: true
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT7855]
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 7E.18.23 p2p_dev_addr=7E.18.23 pri_dev_type=10-0050F204-5  ' A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
,I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715] already in the list, will not add again
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1003","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/WifiP2pService( 1017): P2pEnabledState receive service response
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003] already in the list, will not add again
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1003]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,E/Watchdog( 1017): !@Sync 23,
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 },
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/wpa_supplicant( 1399): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6438","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438]
I/io.jxcore.node.ConnectionHelper( 6074): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT6438], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6074): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT6438] already in the list, will not add again
,E/SMD     (  292): DCD OFF
,I/jxcore-log( 6074): teardown
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): testSendData stopped
I/jxcore-log( 6074): 
,I/io.jxcore.node.ConnectionHelper( 6074): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): shutdown
D/BluetoothSocket( 6074): close() in, this: android.bluetooth.BluetoothSocket@362c7cd6, channel: 6, state: LISTENING
D/BluetoothSocket( 6074): close() this: android.bluetooth.BluetoothSocket@362c7cd6, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@70db11c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@27e8b57mSocket: android.net.LocalSocket@3aa00644 impl:android.net.LocalSocketImpl@14a3932d fd:FileDescriptor[110]
,D/BluetoothSocket( 6074): Closing mSocket: android.net.LocalSocket@3aa00644 impl:android.net.LocalSocketImpl@14a3932d fd:FileDescriptor[110]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6074): Exiting thread
D/WifiP2pService( 1017): InactiveState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6074): onServerStopped
D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6074): release: No more listeners, de-initializing...
D/WifiP2pService( 1017): P2pEnabledState clear service
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6074): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6074): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6074): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6074): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6074): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6074): setState: NOT_STARTED
,I/jxcore-log( 6074): StopBroadcasting went ok
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): 2015-12-23T02:17:58.180Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 6074): 
,I/chromium( 6074): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6074): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6074): onDiscoveryManagerStateChanged: NOT_STARTED,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6074): Local services cleared successfully
D/WifiP2pService( 1017): InactiveState{ what=139268 }
I/wpa_supplicant( 1399): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6074): P2P device discovery stopped successfully
D/WifiP2pService( 1017): InactiveState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState clear service request
,D/WifiP2pService( 1017): remove channel information from framework
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
I/jxcore-log( 6074): ****TEST TOOK:  ms ****
I/jxcore-log( 6074): 
I/jxcore-log( 6074): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6074): 
D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6074): Service requests cleared successfully
,D/AndroidRuntime( 6807): 
D/AndroidRuntime( 6807): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6807): CheckJNI is OFF,
D/AndroidRuntime( 6807): readGMSProperty: start
D/AndroidRuntime( 6807): readGMSProperty: already setted!!
D/AndroidRuntime( 6807): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6807): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6807): readGMSProperty: end
D/AndroidRuntime( 6807): addProductProperty: start
,E/AffinityControl( 6807): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6807): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PackageManager( 1017): START PACKAGE DELETE: observer{902421394}
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1017): !@killApplicatoin: 10338, uninstall pkg
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
,I/ActivityManager( 1017): Killing 6074:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1017): Skipping PackageSetting{3cc9af6c com.example.hello/10346} due to missing metadata
,I/WindowState( 1017): WIN DEATH: Window{31909367 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1017): Focus left window: 6074
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{252750dd u0 com.test.thalitest/.MainActivity t20}
,W/ActivityManager( 1017): Spurious death for ProcessRecord{cc52963 6074:com.test.thalitest/u0a338}, curProc for 6074: null
,D/InputDispatcher( 1017): Focused application released
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 4066): Explicit concurrent mark sweep GC freed 3212(192KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 914us total 36.417ms
,I/art     ( 5951): Explicit concurrent mark sweep GC freed 4084(176KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 6MB/8MB, paused 1.012ms total 44.420ms
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1704): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 1847): mOCRHelper is null
,I/KLMS-2.5.123: ( 3681): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 23 03:17:58 GMT+01:00 2015
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3681): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1017): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1017): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1017): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3681): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/Zygote  ( 6820): MountEmulatedStorage()
E/Zygote  ( 6820): v2
I/libpersona( 6820): KNOX_SDCARD checking this for 10090
I/libpersona( 6820): KNOX_SDCARD not a persona
D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
,I/SELinux ( 6820): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6820): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6820): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6820 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3681): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,W/TextServicesManagerService( 1017): no available spell checker services found
,D/TimaKeyStoreProvider( 6820): TimaSignature is unavailable
,D/ActivityThread( 6820): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): PACKAGE_REMOVED
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/RegisteredServicesCache( 1441): empty dynamic service
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 24091(1882KB) AllocSpace objects, 6(100KB) LOS objects, 33% free, 24MB/36MB, paused 3.499ms total 208.920ms
,I/art     ( 1017): WaitForGcToComplete blocked for 164.321ms for cause Explicit
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 6820): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6820): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6820): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6820): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 6820): ElmAgentService : onCreate()
,D/elm:15121( 6820): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 6820): MainReceiver.listeningToPackageRemoved()
,D/elm:15121( 6820): MDMBridge.getInstance()
,D/elm:15121( 6820): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 6820): MDMBridge.getAllLicenseInfoFromSDK()
,D/RCPManagerService( 1017): PackageReceiver onReceive()
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 6820): ElmAgentService : onDestroy().
,I/ActivityManager( 1017): Killing 5804:com.wsomacp/u0a23 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): onDestroy()
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 8808(417KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 3.043ms total 163.888ms
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1017): delete codoeFile: 
,D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1017): UID=10338 Target=com.test.thalitest
,D/PackageManager( 1017): result of delete: 1{902421394}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AndroidRuntime( 6807): Shutting down VM
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/UsbSettingsManager( 1017): clearDefaults: com.test.thalitest
,D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10338
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,I/CrashAnrDetector( 1017): onPackageRemoved : com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,W/libprocessgroup( 1017): failed to open /acct/uid_10023/pid_5804/cgroup.procs: No such file or directory
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10338
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=20_task.xml
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,I/PCWCLIENTTRACE_PushUtil( 5651): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5651): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5651): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5651): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6837): MountEmulatedStorage()
,E/Zygote  ( 6837): v2
I/libpersona( 6837): KNOX_SDCARD checking this for 10029
I/libpersona( 6837): KNOX_SDCARD not a persona
,I/SELinux ( 6837): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6837 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 6837): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6837): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6837): TimaSignature is unavailable
,D/ActivityThread( 6837): Added TimaKeyStore provider
,I/SA      ( 5840): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5840): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/FeatureConfig( 6837): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/ActivityManager( 1017): Killing 5823:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/ResourcesManager( 6837): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6837): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/PackagesMonitor( 4955): PackagesMonitor onReceive :com.test.thalitest
,W/ResourcesManager( 6837): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ResourcesManager( 6837): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6837): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6837): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
W/ResourcesManager( 6837): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.,
,W/ResourcesManager( 6837): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6837): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6837): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6837): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6837): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6837): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/Zygote  ( 6856): MountEmulatedStorage(),
I/libpersona( 6856): KNOX_SDCARD checking this for 10041
E/Zygote  ( 6856): v2
I/libpersona( 6856): KNOX_SDCARD not a persona
I/SELinux ( 6856): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=6856 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a,
,I/SELinux ( 6856): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ResourcesManager( 6837): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
W/ResourcesManager( 6837): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/SELinux ( 6856): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/art     ( 6807): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,I/art     (  308): Explicit concurrent mark sweep GC freed 8681(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 628us total 23.458ms
,W/ResourcesManager( 6837): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6856): TimaSignature is unavailable
D/ActivityThread( 6856): Added TimaKeyStore provider
,W/ResourcesManager( 6837): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 16.906ms
,W/ResourcesManager( 6856): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6856): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6837): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 16.521ms
W/ResourcesManager( 6856): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6856): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6837): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6856): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6837): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6837): system/finder_cp/cpdata.xml file not found
,D/Mms/MmsApp( 6856): [start]    onCreate() consume time = 0.0
,W/libprocessgroup( 1017): failed to open /acct/uid_10048/pid_5823/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder

```
