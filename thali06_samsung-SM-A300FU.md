#### Test 5497026140aeaf4_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  296): DCD OFF
,D/AndroidRuntime( 6151): 
D/AndroidRuntime( 6151): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6151): CheckJNI is OFF
D/AndroidRuntime( 6151): readGMSProperty: start
D/AndroidRuntime( 6151): readGMSProperty: already setted!!
D/AndroidRuntime( 6151): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6151): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6151): readGMSProperty: end
D/AndroidRuntime( 6151): addProductProperty: start
E/AffinityControl( 6151): AffinityControl: registerfunction enter
D/AndroidRuntime( 6151): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1020): inState():  stateMachine is null !!
I/PersonaManagerService( 1020): PersonaId don't exist
I/ActivityManager( 1020): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
W/ActivityManager( 1020): mDVFSHelper.acquire()
D/FocusedStackFrame( 1020): Set to : 0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1020): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1020): *FMB* installDecor flags : 25362712
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6165 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1020): Focused application set to: xxxx
D/InputDispatcher( 1020): Focus left window: 1499
D/AndroidRuntime( 6151): Shutting down VM
E/Zygote  ( 6165): MountEmulatedStorage()
E/Zygote  ( 6165): v2
I/libpersona( 6165): KNOX_SDCARD checking this for 10338
I/libpersona( 6165): KNOX_SDCARD not a persona
I/SELinux ( 6165): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6165): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6165): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, uhalitest
I/art     (  314): Explicit concurrent mark sweep GC freed 8690(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 624us total 21.071ms
D/TimaKeyStoreProvider( 6165): TimaSignature is unavailable
D/ActivityThread( 6165): Added TimaKeyStore provider
I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.417ms
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
V/WindowManager( 1020): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 18.040ms
D/PersonaManager( 1020): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1499): updateVisibility : ActivityRecord{4b626a3 token=android.os.BinderProxy@3b010b0a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1499): onTrimMemory. Level: 20
I/WebViewFactory( 6165): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6165): Time to load native libraries: 2 ms (timestamps 2149-2151)
I/LibraryLoader( 6165): Expected native library version number "",actual native library version number ""
W/art     ( 6151): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6165): Binding Chromium to main looper Looper (main, tid 1) {37518141}
I/LibraryLoader( 6165): Expected native library version number "",actual native library version number ""
I/chromium( 6165): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6165): Initializing chromium process, singleProcess=true
W/art     ( 6165): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6165): ApplicationContext is null in ApplicationStatus
W/chromium( 6165): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6165): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6165): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6165): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6165): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6165): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6165): Local Branch: 
I/Adreno-EGL( 6165): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6165): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6165):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/art     ( 6165): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6165): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 6165): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6165): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6165): CordovaWebView is running on device made by: samsung
W/art     ( 6165): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6165): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1020): Activity pause timeout for ActivityRecord{a28d64b u0 com.test.thalitest/.MainActivity t20}
D/OpenGLRenderer( 6165): Render dirty regions requested: true
D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
W/chromium( 6165): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6165): updateVisibility : ActivityRecord{d87d522 token=android.os.BinderProxy@35ba0d04 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 6165): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6165): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1020): Focus entered window: 6165
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6165): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6165): Initialized EGL, version 1.4
D/OpenGLRenderer( 6165): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6165): Enabling debug mode 0
D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager( 1020): Displayed Component not be shown by security: +633ms (total +35s489ms)
W/ActivityManager( 1020): mDVFSHelper.release()
I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{a28d64b u0 com.test.thalitest/.MainActivity t20} time:152642
I/SurfaceFlinger(  258): id=12 Removed uhalitest (7/9)
I/SurfaceFlinger(  258): id=12 Removed uhalitest (-2/9)
W/IInputConnectionWrapper( 6165): showStatusIcon on inactive InputConnection
I/Timeline( 6165): Timeline: Activity_idle id: android.os.BinderProxy@35ba0d04 time:152655
I/SamsungIME( 1837): getCurrentCandidateView
D/SamsungIME( 1837): Dismiss ExpandCandiate
I/SamsungIME( 1837): getDebugLevel  : 0x4f4c
W/BindingManager( 6165): Cannot call determinedVisibility() - never saw a connection for the pid: 6165
I/SamsungIME( 1837): getDebugLevel  : 0x4f4c
I/SamsungIME( 1837): KeybaordView init() : load resources
I/SamsungIME( 1837): getCurrentKeyboard
I/SamsungIME( 1837): getTextKeyboard
D/SamsungIME( 1837): [SwiftkeyWrapper] currentLangauge : 1701729619
V/AlarmManager( 1020): waitForAlarm result :4
I/BooksSync( 6089): Starting books sync for 61035162, extras: ade
D/JsMessageQueue( 6165): Set native->JS mode to OnlineEventsBridgeMode
I/BooksConfig( 6089): GmsCore Version = 7.8.99 (2134222-434)
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
I/art     ( 1723): Explicit concurrent mark sweep GC freed 17761(1015KB) AllocSpace objects, 3(60KB) LOS objects, 40% free, 7MB/12MB, paused 979us total 51.020ms
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/GLSUser ( 1723): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1723): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1723): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1723): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1723): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1723): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1723): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1723): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6089): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6089): Soft error
E/BooksSync( 6089): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6089): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6089): Sync error
E/BooksSync( 6089): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6089): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6089): Finished books sync
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 152917, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/jxcore_app_log( 6165): JniHelper::setJavaVM(0xb828a448), pthread_self() = -1199690672
,D/JX-Cordova( 6165): jxcore cordova android initializing
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,I/PowerManagerService( 1020): [PWL] Off : 75s ago
,W/jxcore-log( 6165): Initializing JXcore engine
W/jxcore-log( 6165): JXcore engine is ready
,E/SMD     (  296): DCD OFF
,W/jxcore-log( 6165): Starting JXcore engine
,E/audit   ( 1857): type=1400 msg=audit(1452278349.515:205): avc:  denied  { ioctl } for  pid=6165 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1857):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1857): type=1300 msg=audit(1452278349.515:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=beb10d58 items=0 ppid=314 ppcomm=main pid=6165 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1857): type=1320 msg=audit(1452278349.515:205): 
,W/jxcore-log( 6165): Platform android
W/jxcore-log( 6165): 
W/jxcore-log( 6165): Process ARCH arm
W/jxcore-log( 6165): 
,I/jxcore-log( 6165): JXcore Cordova bridge is ready!,
I/jxcore-log( 6165): 
W/jxcore-log( 6165): JXcore engine is started
I/chromium( 6165): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6165): Toggling radios to true
I/jxcore-log( 6165): 
,D/BluetoothAdapter( 6165): enable(),
,D/BluetoothAdapter( 6165): enable(): BT is already enabled..!,
,D/SecContentProvider( 1020): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1020): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1020): mCursor = null
,D/WifiService( 1020): setWifiEnabled: true pid=6165, uid=10338
,W/ActivityManager( 1020): Permission Denial: getCurrentUser() from pid=6165, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1020): Failed getting userId using ActivityManagerNative
W/WifiService( 1020): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6165, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1020): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1020): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1020): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1020): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1020): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1020): name = wifi_on
I/WifiService( 1020): disconnect: pid=6165, uid=10338
I/wpa_supplicant( 1397): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 6165): Radios toggled
I/jxcore-log( 6165): 
,I/wpa_supplicant( 1397): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1,
I/wpa_supplicant( 1397): wlan0: State: COMPLETED -> DISCONNECTED
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1397): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1397): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030,
I/wpa_supplicant( 1397): wlan0: State: DISCONNECTED -> DISCONNECTED
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
,D/Tethering( 1020): InitialState.processMessage what=4
E/wpa_supplicant( 1397): Cmd 35605 not handled
,E/WifiStateMachine( 1020): WifiStateMachine: Leaving Connected state
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1397): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1397): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1397): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1397): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1397): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1397): First Scan Start
,I/wpa_supplicant( 1397): Scan requested (ret=0) - scan timeout 30 seconds
,E/Tethering( 1020): No numeric data
D/Tethering( 1020): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1020): clearTetheredNotification()
E/WifiConfigStore( 1020): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,V/NetworkStats( 1020): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
,D/Tethering( 1020): interfaceLinkStateChanged wlan0, false,
,D/Tethering( 1020): interfaceStatusChanged wlan0, false
D/HotspotTile( 1180): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1180): updateTetherState():false, false
,I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
,V/NetworkStats( 1020): performPollLocked() took 8ms
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,E/WifiNative-wlan0( 1020): do suspend true
,D/WifiP2pService( 1020): InactiveState{ what=143375 }
,D/WifiP2pService( 1020): P2pEnabledState{ what=143375 }
,D/CommandListener(  279): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/ConnectivityService( 1020): updateNetworkInfo()
E/ConnectivityService( 1020): updateNetworkInfo()
E/WifiStateMachine( 1020): Start Disconnecting Watchdog 1
,V/NativeCrypto( 1723): Read error: ssl=0xb87816e8: I/O error during system call, Connection timed out
I/wpa_supplicant( 1397): wlan0: Setting scan request: 0 sec 0 usec
,I/WifiTrafficPoller( 1020): evaluateTrafficStatsPolling
,V/NativeCrypto( 1723): SSL shutdown failed: ssl=0xb87816e8: I/O error during system call, Broken pipe
,E/WifiNative-wlan0( 1020): do suspend true
,I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7f2a7c8,
D/WifiP2pService( 1020): InactiveState{ what=143375 }
I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
D/WifiP2pService( 1020): P2pEnabledState{ what=143375 }
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
D/ConnectivityService( 1020): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1208833912)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1020): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1020): Tagging socket 338 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1020, getuid(): 1000
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qtaguid ( 1020): Untagging socket 338
,I/System.out( 1020): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1308): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/Hs20UtilService( 2133): Starting #8
,I/NearbySettings( 1308): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1308): MountReceiver.onReceive - Set preference state off
I/Hs20UtilService( 2133): Message received 5007
,V/NearbySettings( 1308): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504,
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1208833912) wakelock released: 1, error no: 0
I/rmt_storage(  273): 
,I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7f2a7c8
,E/Zygote  ( 6220): MountEmulatedStorage()
I/ActivityManager( 1020): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6220 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/Zygote  ( 6220): v2
I/libpersona( 6220): KNOX_SDCARD checking this for 10102
I/libpersona( 6220): KNOX_SDCARD not a persona
,I/SELinux ( 6220): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6220): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6220): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener(  279): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/ConnectivityService( 1020): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Validated
D/ConnectivityService( 1020): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1020): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI_P2P( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1020): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1020): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/TelephonyNetworkFactory( 1477): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1477): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WifiTrafficPoller( 1020): evaluateTrafficStatsPolling
,D/EntConnectivity( 1020): Not allowed due to - mEnabled false - primarySimSlot false
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1020): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): doQuit - quitNow()
,D/EntConnectivity( 1020): Not allowed due to - mEnabled false - primarySimSlot false
D/Tethering( 1020): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1020): MasterInitialState.processMessage what=3
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): updateIfacesLocked()
D/WifiNetworkAgent( 1020): NetworkAgent: NetworkAgent channel lost
V/NetworkStats( 1020): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): performPollLocked() took 4ms
D/StatusBar.NetworkController( 1180): EthernetConnected: false
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1180): updateDataNetType()
D/StatusBar.NetworkController( 1180): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1180): updateLTEICONDataNetType:0
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/WIFI    ( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1180): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/TimaKeyStoreProvider( 6220): TimaSignature is unavailable
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ActivityThread( 6220): Added TimaKeyStore provider
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
,W/ResourcesManager( 6220): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,D/PhoneApp( 1477): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,D/FileWriteThread_Telephony( 1477): FileWriteThread : threadType = 3
,I/Babel_SMS( 6220): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6220): MmsConfig.loadMmsSettings
I/Babel_SMS( 6220): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel_SMS( 6220): MmsConfig.loadFromDatabase
E/Babel_SMS( 6220): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6220): MmsConfig.loadFromResources
E/Babel_SMS( 6220): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6220): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
W/QCamera2Factory(  288): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  288): getCameraInfo: X
W/QCamera2Factory(  288): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  288): getCameraInfo: X
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
W/Settings( 6220): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6220): startup - clean
I/Babel   ( 6220): deleted: false for 0
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 2133): Starting #9
I/Hs20UtilService( 2133): Message received 5007
D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1308): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1308): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1308): MountReceiver.mPrefHandler - 7002
W/VideoCapabilities( 6220): Unrecognized profile 2130706433 for video/avc
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/AudioCapabilities( 6220): Unsupported mime audio/evrc
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/AudioCapabilities( 6220): Unsupported mime audio/qcelp
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/AudioCapabilities( 6220): Unsupported mime audio/mpeg-L1
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/AudioCapabilities( 6220): Unsupported mime audio/mpeg-L2
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/GpsLocationProvider( 1020): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
W/AudioCapabilities( 6220): Unsupported mime audio/x-ms-wma
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/ApplicationPolicy( 1020): updateDataUsageMap
W/AudioCapabilities( 6220): Unsupported mime audio/x-ima
W/AudioCapabilities( 6220): Unsupported mime audio/qcelp
W/AudioCapabilities( 6220): Unsupported mime audio/evrc
W/VideoCapabilities( 6220): Unsupported mime video/wvc1
W/VideoCapabilities( 6220): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6220): Unrecognized profile/level 32768/2 for video/mp4v-es
W/VideoCapabilities( 6220): Unsupported mime video/wvc1
W/VideoCapabilities( 6220): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6220): Unsupported mime video/x-ms-wmv7
W/VideoCapabilities( 6220): Unsupported mime video/x-ms-wmv8
W/VideoCapabilities( 6220): Unsupported mime video/mp43
W/VideoCapabilities( 6220): Unsupported mime video/sorenson
W/VideoCapabilities( 6220): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6220): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6220): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6220): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6220): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6220): Unrecognized profile 2130706433 for video/avc
I/ActivityManager( 1020): Killing 5657:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
I/vclib   ( 6220): onServiceConnected
W/Babel   ( 6220): Attempted to change video mute state without an active call.
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1020): failed to open /acct/uid_10139/pid_5657/cgroup.procs: No such file or directory
I/wpa_supplicant( 1397): nl80211: Received scan results (7 BSSes)
I/wpa_supplicant( 1397): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1397): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1397): Trying to associate with  'G700'
I/wpa_supplicant( 1397): Re-associate with C0.AA.48
I/wpa_supplicant( 1397): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1397): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1020): didn't find BSSID Trying to associate with SSID 'NG700'
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/PCWCLIENTTRACE_PushUtil( 5724): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5724): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5724): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5724): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/splitIntent( 1020): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1020): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1020): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
I/PCWCLIENTTRACE_SYSTEMReceiver( 5724): noConnectivity : true
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6265): MountEmulatedStorage()
I/ActivityManager( 1020): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6265 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6265): v2
I/libpersona( 6265): KNOX_SDCARD checking this for 10108
I/libpersona( 6265): KNOX_SDCARD not a persona
I/SELinux ( 6265): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6265): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6265): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6265): TimaSignature is unavailable
D/ActivityThread( 6265): Added TimaKeyStore provider
E/wpa_supplicant( 1397): Cmd 35605 not handled
I/wpa_supplicant( 1397): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1397): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1397): Associated with C0.AA.48
I/wpa_supplicant( 1397): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1397): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1397): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1397): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1397): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1397): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1397): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1397): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1397): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1397): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1397): Blacklist: Clear (temp) 
I/wpa_supplicant( 1397): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceLinkStateChanged wlan0, true
D/Tethering( 1020): interfaceStatusChanged wlan0, true
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, true
E/Tethering( 1020): No numeric data
D/Tethering( 1020): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1020): clearTetheredNotification()
D/Tethering( 1020): interfaceLinkStateChanged wlan0, true
D/Tethering( 1020): interfaceStatusChanged wlan0, true
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, true
V/NetworkStats( 1020): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/HotspotTile( 1180): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
D/HotspotTile( 1180): updateTetherState():false, false
D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
D/WifiNative-wlan0( 1020): callSECApiVoid - ID [50]
E/WifiConfigStore( 1020): setLastSelectedConfiguration -1
V/NetworkStats( 1020): performPollLocked() took 7ms
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/ConnectivityService( 1020): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1020): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1020): updateNetworkInfo()
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/WifiConfigStore( 1020): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
E/WifiConfigStore( 1020): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  279): Setting iface cfg
E/WifiStateMachine( 1020): Start Dhcp Watchdog 2
I/MusicStore( 6265): Database version: 120
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
E/WifiNative-wlan0( 1020): do suspend false
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
V/EmergencyMode( 1438): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1438): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/WifiP2pService( 1020): InactiveState{ what=143375 }
D/WifiP2pService( 1020): P2pEnabledState{ what=143375 }
V/HeadsetService( 2660): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2660): Disconnected process message: 10
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6265): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6265): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/ContextImpl( 6265): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ResourcesManager( 6265): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6265): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6265): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/SQLiteLog( 1723): (10) POSIX Error : 11 SQLite Error : 3850
,E/dhcpcd  ( 6291): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 6291): version 5.5.6 starting
,E/dhcpcd  ( 6291): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
W/ActivityThread( 6265): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6265): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c33bcde: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6265): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6265): GMSCore installation verified
,I/ConfigStore( 6265): Config Database version: 1
,I/dhcpcd  ( 6291): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6291): wlan0: sendmsg: Cannot assign requested address
,I/dhcpcd  ( 6291): if(wlan0) info get Success. (MAC : C0.AA.48),
I/dhcpcd  ( 6291): bssid match
,I/dhcpcd  ( 6291): wlan0: rebinding lease of 192.168.1.132
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1020): getStreamVolume 3 index 70
,I/MediaRouter( 6265): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6265): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6302 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6302): MountEmulatedStorage()
I/libpersona( 6302): KNOX_SDCARD checking this for 10001
E/Zygote  ( 6302): v2
I/libpersona( 6302): KNOX_SDCARD not a persona
,I/SELinux ( 6302): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6302): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6302): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GHttpClientFactory( 6265): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6302): TimaSignature is unavailable
,D/ActivityThread( 6302): Added TimaKeyStore provider
,I/GoogleURLConnFactory( 6265): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1020): Killing 4179:com.sec.spp.push/u0a32 (adj 15): empty #31
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6321 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/ActivityManager( 1020): Killing 5340:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,E/Zygote  ( 6321): MountEmulatedStorage()
E/Zygote  ( 6321): v2
I/libpersona( 6321): KNOX_SDCARD checking this for 1000
I/libpersona( 6321): KNOX_SDCARD not a persona
,I/SELinux ( 6321): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6321): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6321): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6321): TimaSignature is unavailable
,D/ActivityThread( 6321): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 6321): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1020): failed to open /acct/uid_10032/pid_4179/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10014/pid_5340/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6321): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6321): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6321): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6321): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6321): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6321): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6336): MountEmulatedStorage(),
I/ActivityManager( 1020): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6336 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6336): v2
I/libpersona( 6336): KNOX_SDCARD checking this for 10008
I/SELinux ( 6336): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 6336): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Killing 5240:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,I/SELinux ( 6336): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6336): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6336): TimaSignature is unavailable
,D/ActivityThread( 6336): Added TimaKeyStore provider
,E/SMD     (  296): DCD OFF
,I/ActivityManager( 1020): Killing 5701:com.samsung.helphub/1000 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3656): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 19:39:12 GMT+01:00 2016
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3656): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 3656): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3656): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3656): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  ( 6352): MountEmulatedStorage(),
E/Zygote  ( 6352): v2
I/libpersona( 6352): KNOX_SDCARD checking this for 10031
I/SELinux ( 6352): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/libpersona( 6352): KNOX_SDCARD not a persona
,I/SELinux ( 6352): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6352): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6352 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
I/KLMS-2.5.123: ( 3656): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
D/TimaKeyStoreProvider( 6352): TimaSignature is unavailable
D/ActivityThread( 6352): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3656): StateImplV2(): networkChangeListener().END
I/KLMS-2.5.123: ( 3656): KLMSIntentService(): onDestroy()
,I/SO_AGENT( 6352): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5754): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5812): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5812): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 5812): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5754): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/SA      ( 5812): [SLFUCHKMGR] constructor called
I/DBG_POLICYDM( 5754): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
E/DBG_POLICYDM( 5754): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
E/DBG_POLICYDM( 5754): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 5812): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5812): [OR] == isSIMCardReady false ==
,I/SA      ( 5812): [SCU] == networkStateCheck == false
,I/SA      ( 5812): [OR] onReceive END
,I/ActivityManager( 1020): Killing 5739:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,V/DownloadManager( 1227): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1587): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,W/libprocessgroup( 1020): failed to open /acct/uid_10032/pid_5240/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_5701/cgroup.procs: No such file or directory
,D/daemonapp( 1637): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1587): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1587): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1587): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1587): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1587): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1587): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6369): MountEmulatedStorage()
E/Zygote  ( 6369): v2
,I/libpersona( 6369): KNOX_SDCARD checking this for 10121
I/libpersona( 6369): KNOX_SDCARD not a persona
,I/SELinux ( 6369): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6369): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6369): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1020): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6369 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,D/TimaKeyStoreProvider( 6369): TimaSignature is unavailable
,D/ActivityThread( 6369): Added TimaKeyStore provider
,W/ResourcesManager( 6369): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6369): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6369): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6369): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6369): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6369): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1020): failed to open /acct/uid_10087/pid_5739/cgroup.procs: No such file or directory
,E/Zygote  ( 6384): MountEmulatedStorage()
I/libpersona( 6384): KNOX_SDCARD checking this for 10141
E/Zygote  ( 6384): v2
I/libpersona( 6384): KNOX_SDCARD not a persona
,I/SELinux ( 6384): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6384 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/SELinux ( 6384): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6384): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Killing 5356:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6384): TimaSignature is unavailable
,D/ActivityThread( 6384): Added TimaKeyStore provider
,W/ResourcesManager( 6384): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6384): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6384): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6384): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,W/libprocessgroup( 1020): failed to open /acct/uid_10029/pid_5356/cgroup.procs: No such file or directory
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/BadgeProvider( 5875): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 1499): reloadBadges entered.
D/BadgeProvider( 5875): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5875): sendNotify, [notify] : null
D/BadgeProvider( 5875): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5875): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5875): update, [UpdateCount] : 1
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6407): MountEmulatedStorage(),
I/ActivityManager( 1020): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6407 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
E/Zygote  ( 6407): v2
I/libpersona( 6407): KNOX_SDCARD checking this for 1000,
I/libpersona( 6407): KNOX_SDCARD not a persona
,I/SELinux ( 6407): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 6407): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6407): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6407): TimaSignature is unavailable
,D/ActivityThread( 6407): Added TimaKeyStore provider
,D/SecurityLogAgent( 6407): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6407): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6407): StateMachine : Current State = 1
,D/SecurityLogAgent( 6407): StateMachine : Changed Current State = 1,
,I/ActivityManager( 1020): Killing 5794:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/iu.Environment( 1854): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/iu.UploadsManager( 1854): num queued entries: 0
,I/iu.UploadsManager( 1854): num updated entries: 0
I/iu.SyncManager( 1854): NEXT; no task
I/art     ( 1020): Explicit concurrent mark sweep GC freed 56983(3MB) AllocSpace objects, 5(132KB) LOS objects, 33% free, 23MB/35MB, paused 3.060ms total 215.928ms
,E/Zygote  ( 6426): MountEmulatedStorage(),
E/Zygote  ( 6426): v2
I/libpersona( 6426): KNOX_SDCARD checking this for 10032,
I/libpersona( 6426): KNOX_SDCARD not a persona
,I/SELinux ( 6426): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6426): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6426 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup( 1020): failed to open /acct/uid_10148/pid_5794/cgroup.procs: No such file or directory
,E/SELinux ( 6426): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 6220): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager( 1020): Killing 5831:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6426): TimaSignature is unavailable
,W/ActivityManager( 1020): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/ActivityThread( 6426): Added TimaKeyStore provider
,E/SPPClientService( 6426): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6426): [SystemStateMoniter] Current Time : 158157
,E/SPPClientService( 6426): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6426): [SystemStateMoniter] No Connect : true
E/SPPClientService( 6426): [PushClientApplication] Push log off : This is Ship build version
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6443): MountEmulatedStorage()
,E/Zygote  ( 6443): v2
I/libpersona( 6443): KNOX_SDCARD checking this for 10110
I/libpersona( 6443): KNOX_SDCARD not a persona
,I/SELinux ( 6443): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/SPPClientService( 6426): PushLog.txt file is not deleted.
D/SPPClientService( 6426): PushLog.txt file is not deleted.
D/SPPClientService( 6426): ============PushLog. stop!
,I/dhcpcd  ( 6291): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
I/SELinux ( 6443): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6443): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6443 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 5065:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SPPClientService( 6426): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 6443): TimaSignature is unavailable
,D/ActivityThread( 6443): Added TimaKeyStore provider
,I/art     (  314): Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 618us total 27.578ms
,W/libprocessgroup( 1020): failed to open /acct/uid_10152/pid_5831/cgroup.procs: No such file or directory
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 16.872ms
,I/dhcpcd  ( 6291): wlan0: leased 192.168.1.132 for 86400 seconds
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 17.618ms
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/libprocessgroup( 1020): failed to open /acct/uid_10039/pid_5065/cgroup.procs: No such file or directory,
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6443): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache,
,I/GAv4    ( 6443): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6443):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6443):   adb logcat -s GAv4
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6443): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6443): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/GAv4    ( 6443): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6443): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6443): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6443): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/WifiNative-wlan0( 1020): do suspend true
,D/WifiP2pService( 1020): InactiveState{ what=143375 }
,D/WifiP2pService( 1020): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1020): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,E/WifiStateMachine( 1020): VerifyingLinkState enter
,D/WifiNative-wlan0( 1020): callSECApiInt - ID [210]
,E/ConnectivityService( 1020): updateNetworkInfo()
,D/ConnectivityService( 1020): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1020): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1020): updateDnsLinkProperty: enter
,D/ConnectivityService( 1020): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/WifiWatchdogStateMachine.DnsPinger( 1020): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 1020): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1020): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1020): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1020): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1020): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/WifiStateMachine( 1020): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,E/ConnectivityService( 1020): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1020): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1020): LTETest block dns file not exists
,D/ConnectivityService( 1020): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,E/ConnectivityService( 1020): updateNetworkInfo()
,E/ConnectivityService( 1020): updateNetworkInfo()
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1020): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1020): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/WebViewFactory( 6443): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,D/ConnectivityService( 1020):    accepting network in place of null
,I/System.out( 1020): (HTTPLog)-Static: isSBSettingEnabled false
,D/TelephonyNetworkFactory( 1477): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true,
D/TelephonyNetworkFactory( 1477): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine( 1020): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WIFI_P2P( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
I/WifiTrafficPoller( 1020): evaluateTrafficStatsPolling
D/CSLegacyTypeTracker( 1020): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
E/CSLegacyTypeTracker( 1020): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine( 1020): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WIFI    ( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 1000
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1020): evaluateTrafficStatsPolling
,I/WifiTrafficPoller( 1020): mBoosterFLAG : 0
I/WifiTrafficPoller( 1020): current booster mode : FullMode
,D/WifiNative-wlan0( 1020): callSECApiVoid - ID [212],
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1020): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1020): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/Tethering( 1020): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/EntConnectivity( 1020): Not allowed due to - mEnabled false - primarySimSlot false
D/Tethering( 1020): MasterInitialState.processMessage what=3
,V/NetworkStats( 1020): updateIfacesLocked()
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
,D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524290
,D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): performPollLocked() took 5ms
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1180): EthernetConnected: false
,D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1180): updateDataNetType()
D/StatusBar.NetworkController( 1180): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1180): updateLTEICONDataNetType:0
I/LibraryLoader( 6443): Time to load native libraries: 2 ms (timestamps 8688-8690)
I/LibraryLoader( 6443): Expected native library version number "",actual native library version number ""
,D/StatusBar.NetworkController( 1180): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/WebViewChromiumFactoryProvider( 6443): Binding Chromium to main looper Looper (main, tid 1) {36c6dfe7}
,I/LibraryLoader( 6443): Expected native library version number "",actual native library version number ""
,I/chromium( 6443): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/SSRM:n  ( 1020): SIOP:: AP = 300
,I/BrowserStartupController( 6443): Initializing chromium process, singleProcess=true
,W/art     ( 6443): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6443): ApplicationContext is null in ApplicationStatus
,W/chromium( 6443): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6443): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6443): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6443): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6443): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6443): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6443): Local Branch: 
I/Adreno-EGL( 6443): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6443): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6443):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 6443): Requires BLUETOOTH permission
,I/NSApplication( 6443): Starting up...
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6525): MountEmulatedStorage()
E/Zygote  ( 6525): v2
I/libpersona( 6525): KNOX_SDCARD checking this for 10077
,I/libpersona( 6525): KNOX_SDCARD not a persona
,I/SELinux ( 6525): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6525): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6525 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6525): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Killing 5691:com.android.mms/u0a41 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6525): TimaSignature is unavailable
,D/ActivityThread( 6525): Added TimaKeyStore provider
,D/CountryDetector( 1020): No listener is left
,D/WaitQueueForNetworkActivate( 6041): notifyNetworkActivated
,W/ContextImpl( 6041): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1020): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/libprocessgroup( 1020): failed to open /acct/uid_10041/pid_5691/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6041): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6041): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6041): exit::IDLE
D/InitializeManagerStateMachine( 6041): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6041): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6041): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6041): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6041): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6041): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6041): entry::SUCCESS
D/hcjo    ( 6041): AutoUpdateManager:INITCHECK:onInitializeSuccess
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/hcjo    ( 6041): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6041): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/Hs20UtilService( 2133): Starting #10
,I/Hs20UtilService( 2133): Message received 5007
,D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1308): DMSUtil.isNetworkConnected - flag-null, state-null
,D/InitializeManagerStateMachine( 6041): exit::SUCCESS
D/InitializeManagerStateMachine( 6041): entry::IDLE
,I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1308): DMSUtil.isNetworkConnected - P2P: IDLE
,I/ActivityManager( 1020): Killing 5858:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1308): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2133): Starting #11
,I/Hs20UtilService( 2133): Message received 5007
,D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1308): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/NetworkMonitor( 6265): type=WIFI subType= reason=null isConnected=true
,I/Hs20UtilService( 2133): Starting #12
,I/Hs20UtilService( 2133): Message received 5007
,D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1308): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1308): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1308): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1308): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2133): Starting #13
,I/Hs20UtilService( 2133): Message received 5007
,D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1308): MountReceiver.onReceive - Keep current state
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,D/WifiStateMachine( 1020): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1020): uri = 15 selection = getToastGravityEnabledState
D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1020): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5724): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5724): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5724): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5724): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1020): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1020): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1020): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6265): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=4, Uoast
,D/GpsLocationProvider( 1020): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1020): failed to open /acct/uid_10042/pid_5858/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6321): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6321): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6321): ./extraInfo: "NG700"
I/DIAGMON_AGENT( 6321): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService( 1020): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1020
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SRIB_DCS( 1180): log_dcs ThreadedRenderer::initialize entered! 
,I/DBG_POLICYDM( 5754): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5754): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5754): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5754): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6336): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6336): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 3656): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 19:39:14 GMT+01:00 2016
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,V/AlarmManager( 1020): waitForAlarm result :4
,I/KLMS-2.5.123: ( 3656): KLMSAbstractReciever(): onReceive().END.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3656): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3656): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3656): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3656): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3656): NetworkChangeOperations(): uploadRequestLog().START 
,I/DBG_POLICYDM( 5754): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3656): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3656): StateImplV2(): networkChangeListener().END
,I/SA      ( 5812): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5812): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5812): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): onDestroy()
,I/SA      ( 5812): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5812): [OR] == isSIMCardReady false ==
I/DBG_POLICYDM( 5754): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 5812): [SCU] == networkStateCheck == true
I/DBG_POLICYDM( 5754): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
I/SA      ( 5812): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5812): isChinaCountryCode : false
I/SA      ( 5812): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5812): [OR] == networkStateCheck true ==
,E/DBG_POLICYDM( 5754): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 5812): [OR] GetMyCountryZoneTask
,I/SA      ( 5812): [OR] onReceive END
,I/DBG_POLICYDM( 5754): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,V/DownloadManager( 1227): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/accuweather( 1587): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5812): [SRS] prepareGetMyCountryZone
,D/SecContentProvider2( 1020): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1020): mCursor = null
,I/DBG_POLICYDM( 5754): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,D/daemonapp( 1637): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 8
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
D/accuweather( 1587): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1587): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1587): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1587): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
I/SA      ( 5812): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
I/SA      ( 5812): [SSP] query invoked
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,D/accuweather( 1587): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
I/DBG_POLICYDM( 5754): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/accuweather( 1587): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/DBG_POLICYDM( 5754): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/SA      ( 5812): [TPMU] GetMccFromDB : null
,I/SA      ( 5812): [SCU] getMccFromPreferece mcc = 260
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/QuickConnect( 6369): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/SA      ( 5812): [TPM] isNoProxy(default) : true
,I/QuickConnect( 6369): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6369): PeriphStartReceiver.onReceive - no need to start
,E/File    ( 5812): fail readDirectory() errno=2
E/DBG_POLICYDM( 5754): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 6407): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6407): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6407): StateMachine : Current State = 1
,D/SecurityLogAgent( 6407): StateMachine : Changed Current State = 1,
,I/DBG_POLICYDM( 5754): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5754): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,I/iu.Environment( 1854): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1854): num queued entries: 0
,I/iu.UploadsManager( 1854): num updated entries: 0
,I/iu.SyncManager( 1854): NEXT; no task
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1854): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6426): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6426): [SystemStateMoniter] Current Time : 159637
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SPPClientService( 6426): [SystemStateMoniter] No Connect : false
,I/System.out( 6220): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6220): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6220): (HTTPLog)-Static: isShipBuild true
I/System.out( 6220): (HTTPLog)-Thread-1067-843049936: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6220): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10102
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ConnectivityService( 1020): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,I/System.out( 6220): KnoxVpnUidStorageknoxVpnSupported API value returned is false
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6041): AutoUpdateManager:IDLE:execute
,I/GLSUser ( 1723): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1723): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1723): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1723): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/InitializeManagerStateMachine( 6041): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6041): exit::IDLE
D/InitializeManagerStateMachine( 6041): entry::NETWORK_CHECK
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/InitializeManagerStateMachine( 6041): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 6041): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6041): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6041): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6041): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 6041): entry::SUCCESS
D/hcjo    ( 6041): AutoUpdateManager:INITCHECK:onInitializeSuccess
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/hcjo    ( 6041): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6041): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6041): exit::SUCCESS
D/InitializeManagerStateMachine( 6041): entry::IDLE
,I/Babel   ( 6220): connection state changed from DISCONNECTED to CONNECTED
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Kids    ( 1854): [AccountUtils] Account not ready
W/Kids    ( 1854): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1854): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1854): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1854): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1854): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1854): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1854): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1854): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1854): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1854): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1854): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1854): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
,I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) ,
,D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/GCM     ( 1723): Connected
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1723): Message class com.google.f.a.a.p
,I/SA      ( 5812): [RC New] Execute method=[GET] start
,I/SA      ( 5812): [RC New] Security=[true]
,I/System.out( 5812): Thread-985(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5812): Thread-985(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5812): Thread-985(ApacheHTTPLog):isShipBuild true
I/System.out( 5812): Thread-985(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5812): Thread-985(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10036
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/SA      ( 5812): [RC New] [v2liruge] api execute + 599
,I/SA      ( 5812): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 5812): AsyncTask #1 calls detatch()
,I/SA      ( 5812): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5812): [OCP] update openData : PL
,I/SA      ( 5812): [TPMU] getNetworkMcc : 
,I/SA      ( 5812): [SCU] saveMccToPreferece Start
,I/SA      ( 5812): [SCU] RegionMCC : 260
,I/SA      ( 5812): [SSP] query invoked
,I/SA      ( 5812): [TPMU] GetMccFromDB : null
,I/SA      ( 5812): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5812): [SCU] saveMccToPreferece End
,I/SA      ( 5812): [RC New] executeRequest [v2liruge] end. 659
I/SA      ( 5812): [RC New] Execute end
,I/SA      ( 5812): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5812): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 6291): wlan0: sending IPv6 Router Solicitation
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6265): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6265): Stop autocaching.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WearableService( 4450): callingUid 10011, callindPid: 4450
,E/GmsUtils( 6265): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6265): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  258): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  258): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1020): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1020) eventTime = 162780
,D/PowerManagerService( 1020): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1020 (0x0)
,D/PowerManagerService( 1020): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1020, ws=WorkSource{10049}) (elapsedTime=3467)
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  296): DCD OFF,
,I/System.out( 1020): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 18:39:19 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452278358904], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452278358883]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Validated
,D/ConnectivityService( 1020): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1020): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1020): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,D/ConnectivityService( 1020): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524290
,D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/StatusBar.NetworkController( 1180): EthernetConnected: false
,D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1180): updateDataNetType()
D/StatusBar.NetworkController( 1180): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1180): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1180): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5724): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5724): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5724): [GetString-S]
,I/ReactiveServiceManager( 5724): Supported : 1
,D/QSEECOMAPI: ( 1020): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1020): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1020): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1020): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1020): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1020): handleString: Failed to handle string(-4)
E/terrier ( 1020): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 5724): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5724): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5724): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5724): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5724): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5724): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 6291): wlan0: sending IPv6 Router Solicitation
,I/jxcore-log( 6165): Test app app.js loaded
I/jxcore-log( 6165): 
,I/chromium( 6165): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1438): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1438): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2660): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2660): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/Watchdog( 1020): !@Sync 5
,D/SSRM:n  ( 1020): SIOP:: AP = 300
,I/dhcpcd  ( 6291): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6291): wlan0: no IPv6 Routers available
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6041): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6041): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6041): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6041): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6041): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6041): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6041): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6041): entry::IDLE
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6041): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6041): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6041): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6041): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 6041): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6041): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6041): entry::IDLE
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1723): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1723): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1723): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1723): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5422): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5422): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5422): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 40455(2MB) AllocSpace objects, 10(164KB) LOS objects, 33% free, 23MB/35MB, paused 2.541ms total 153.137ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1723): Vacuum at: now=1452278368536 tag=VacuumService
,I/GoogleURLConnFactory( 1723): Using platform SSLCertificateSocketFactory
,W/Uploader( 1723): No account for auth token provided
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1723): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1723): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1723): (HTTPLog)-Static: isShipBuild true
I/System.out( 1723): (HTTPLog)-Thread-201-752027349: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1723): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,I/System.out( 1723): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1723): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1723, getuid(): 10011
,I/qtaguid ( 1723): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1723, getuid(): 10011
,W/Uploader( 1723): No account for auth token provided
,I/System.out( 1723): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1723): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1723, getuid(): 10011
,W/Uploader( 1723): No account for auth token provided
,I/System.out( 1723): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1723): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1723, getuid(): 10011
,W/Uploader( 1723):  no longer exists, so no auth token.
,I/System.out( 1723): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1723): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1723, getuid(): 10011
,W/Uploader( 1723): No account for auth token provided
,I/System.out( 1723): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1723): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1723, getuid(): 10011
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1723): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1723): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1723): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1723): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/PersonaManager( 1180): isKioskContainerExistOnDevice
D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,E/Uploader( 1723): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1723): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1723): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1723): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1723): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1723): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1723): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1723): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1723): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1723): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1723): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1723): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1723): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1723): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1723): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1723, getuid(): 10011
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1723): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1020): Plugged
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
V/EmergencyMode( 1438): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1438): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2660): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2660): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/SMD     (  296): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,V/AlarmManager( 1020): waitForAlarm result :4
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1020): [PWL] Off : 105s ago
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,V/AlarmManager( 1020): waitForAlarm result :4
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1723): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1723): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1723): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1723): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5422): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5422): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5422): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1020): !@Sync 6
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,V/AlarmManager( 1020): waitForAlarm result :8
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,I/Atfwd_Sendcmd(  322): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  322): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 140s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/Watchdog( 1020): !@Sync 7,
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1438): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1438): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2660): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2660): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1438): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1438): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2660): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2660): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1020): !@Sync 8,
,I/PowerManagerService( 1020): [PWL] Off : 180s ago,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6089): Starting books sync for 61035162, extras: ade
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 6089): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1723): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1723): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1723): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1723): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1723): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1723): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1723): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1723): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1723): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6089): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6089): Soft error
E/BooksSync( 6089): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6089): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6089): Sync error
E/BooksSync( 6089): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6089): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6089): Finished books sync
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 276481, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1020): !@Sync 9,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  322): Waiting for service AtCmdFwd...
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  322): Waiting for service AtCmdFwd...,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  322): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,I/PowerManagerService( 1020): [PWL] Off : 225s ago
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/jxcore-log( 6165): --= Surplus to requirements =--
I/jxcore-log( 6165): 
,I/jxcore-log( 6165): ****TEST TOOK:  ms ****
I/jxcore-log( 6165): 
I/jxcore-log( 6165): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6165): 
,E/SMD     (  296): DCD OFF
,D/AndroidRuntime( 6665): 
D/AndroidRuntime( 6665): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6665): CheckJNI is OFF,
D/AndroidRuntime( 6665): readGMSProperty: start
D/AndroidRuntime( 6665): readGMSProperty: already setted!!
D/AndroidRuntime( 6665): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6665): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6665): readGMSProperty: end
D/AndroidRuntime( 6665): addProductProperty: start
,E/AffinityControl( 6665): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6665): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1020): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1020): START PACKAGE DELETE: observer{787887402}
D/PackageManager( 1020): pkg{<packageName>}
D/PackageManager( 1020): user{0}
D/PackageManager( 1020): caller{2000}
D/PackageManager( 1020): flags{3}
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1020): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1020): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1020): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1020): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1020): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1020): !@killApplicatoin: 10338, uninstall pkg
,I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg,
I/ActivityManager( 1020): Killing 6165:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1020): Skipping PackageSetting{1b6666d2 com.example.hello/10346} due to missing metadata
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{a28d64b u0 com.test.thalitest/.MainActivity t20}
,E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
,D/InputDispatcher( 1020): Focus left window: 6165
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1020): Focused application released
,E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
,W/ActivityManager( 1020): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 3939): Explicit concurrent mark sweep GC freed 3208(192KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 892us total 32.222ms
,I/art     ( 6025): Explicit concurrent mark sweep GC freed 95(15KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 930us total 39.229ms
I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1837): mOCRHelper is null
W/GeofencerStateMachine( 1693): Ignoring removeGeofence because network location is disabled.
,W/ResourcesManager( 1477): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/KLMS-2.5.123: ( 3656): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 19:41:45 GMT+01:00 2016
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3656): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1020): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1020): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1020): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 3656): KLMSIntentService(): onCreate()
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3656): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/Zygote  ( 6678): MountEmulatedStorage(),
E/Zygote  ( 6678): v2
,I/libpersona( 6678): KNOX_SDCARD checking this for 10090
I/libpersona( 6678): KNOX_SDCARD not a persona
,I/SELinux ( 6678): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1020): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6678 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6678): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6678): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3656): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/RegisteredServicesCache( 1463): empty dynamic service
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,D/TimaKeyStoreProvider( 6678): TimaSignature is unavailable
,D/ActivityThread( 6678): Added TimaKeyStore provider
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 34136(2MB) AllocSpace objects, 63(1017KB) LOS objects, 33% free, 24MB/36MB, paused 3.113ms total 218.738ms
,I/art     ( 1020): WaitForGcToComplete blocked for 206.309ms for cause Explicit
,D/RCPManagerService( 1020): PackageReceiver onReceive()
,I/HarmonyEASService( 1020): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1020): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/elm:15121( 6678): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6678): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6678): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6678): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:15121( 6678): ElmAgentService : onCreate()
,D/elm:15121( 6678): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 6678): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6678): MDMBridge.getInstance()
,D/elm:15121( 6678): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 6678): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): onDestroy()
,D/EnterpriseDeviceManagerService( 1020): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1020): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1020): no available spell checker services found
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 6678): ElmAgentService : onDestroy().
,I/ActivityManager( 1020): Killing 5898:com.wsomacp/u0a23 (adj 15): empty #31
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1020): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10338
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10338
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
D/SSRM:aZ ( 1020): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
,D/TaskPersister( 1020): removeObsoleteFile: deleting file=20_task.xml
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
,I/PCWCLIENTTRACE_PushUtil( 5724): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5724): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5724): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5724): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 13538(723KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 3.431ms total 182.230ms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6695): MountEmulatedStorage()
E/Zygote  ( 6695): v2
I/libpersona( 6695): KNOX_SDCARD checking this for 10029
I/libpersona( 6695): KNOX_SDCARD not a persona
,I/SELinux ( 6695): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6695 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 6695): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6695): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6695): TimaSignature is unavailable
,D/ActivityThread( 6695): Added TimaKeyStore provider
,W/ResourceType( 1020): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,I/FeatureConfig( 6695): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/SA      ( 5812): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5812): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager( 1020): Killing 5915:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1020): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 6713): MountEmulatedStorage()
I/libpersona( 6713): KNOX_SDCARD checking this for 10039
E/Zygote  ( 6713): v2
I/libpersona( 6713): KNOX_SDCARD not a persona
,I/SELinux ( 6713): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6713): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6713 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux ( 6713): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6713): TimaSignature is unavailable
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityThread( 6713): Added TimaKeyStore provider
,D/PackageManager( 1020): delete codoeFile: 
,D/AASAuninstall( 1020): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/AASA_removePackage( 1020): UID=10338 Target=com.test.thalitest
D/PackageManager( 1020): result of delete: 1{787887402}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AndroidRuntime( 6665): Shutting down VM
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 6713): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6713): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6713): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6713): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6713): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6713): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6713): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/CrashAnrDetector( 1020): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 1020): clearDefaults: com.test.thalitest
,W/libprocessgroup( 1020): failed to open /acct/uid_10023/pid_5898/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10048/pid_5915/cgroup.procs: No such file or directory
,W/ResourcesManager( 6695): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
W/ResourcesManager( 6695): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6695): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6695): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6695): system/finder_cp/cpdata.xml file not found
,D/NearbySource( 6713): Nearby Source Create!
,D/NearbyContext( 6713): Nearby Context Create!
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6713): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 6713): Samsung link source created
,D/ContactProvider( 6713): getAllContactInfoList Start
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/PackagesMonitor( 6713): PackagesMonitor onReceive :com.test.thalitest
,W/art     ( 6665): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,D/ContactProvider( 6713): getAllContactInfoList End
,I/syncContacts( 6713): thread: 1128, sync time = 42
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ProcessCpuTracker( 1020): Skipping unknown process pid 6665
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6734): MountEmulatedStorage()
E/Zygote  ( 6734): v2
I/libpersona( 6734): KNOX_SDCARD checking this for 10041
I/libpersona( 6734): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=6734 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 5932:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31,
I/SELinux ( 6734): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6734): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6734): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6734): TimaSignature is unavailable,
D/ActivityThread( 6734): Added TimaKeyStore provider
,W/ResourcesManager( 6734): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6734): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6734): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6734): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6734): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/Mms/MmsApp( 6734): [start]    onCreate() consume time = 0.0
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_5932/cgroup.procs: No such file or directory

```
