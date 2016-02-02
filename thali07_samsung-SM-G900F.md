#### Test 575312431f256a6_thali07_samsung-SM-G900F Logs


```
--------- beginning of system
W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
E/SMD     (  285): DCD ON
W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager(  842): waitForAlarm result :8
V/AlarmManager(  842): waitForAlarm result :8
D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ResourcesManager( 1638): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
D/AndroidRuntime( 7229): 
D/AndroidRuntime( 7229): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7229): CheckJNI is OFF
D/AndroidRuntime( 7229): setted country_code = Germany
D/AndroidRuntime( 7229): setted countryiso_code = DE
D/AndroidRuntime( 7229): setted sales_code = DBT
D/AndroidRuntime( 7229): readGMSProperty: start
D/AndroidRuntime( 7229): readGMSProperty: already setted!!
V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/AndroidRuntime( 7229): readGMSProperty: end
D/AndroidRuntime( 7229): addProductProperty: start
D/SecContentProvider2(  842): uri = 14 selection = getSealedState
D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/Search.LoginHelper( 1547): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
D/SSRM:m  (  842): SIOP:: AP = 360, PST = 431, CUR = 300
E/AffinityControl( 7229): AffinityControl: registerfunction enter
D/AndroidRuntime( 7229): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  842): inState():  stateMachine is null !!
V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  842): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  842): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  842): mDVFSHelper.acquire()
D/FocusedStackFrame(  842): Set to : 0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7269): MountEmulatedStorage()
E/Zygote  ( 7269): v2
I/libpersona( 7269): KNOX_SDCARD checking this for 10200
I/libpersona( 7269): KNOX_SDCARD not a persona
I/ActivityManager(  842): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7269 uid=10200 gids={50200, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SELinux ( 7269): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7269): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/AndroidRuntime( 7229): Shutting down VM
E/SELinux ( 7269): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/TimaKeyStoreProvider( 7269): TimaSignature is unavailable
D/ActivityThread( 7269): Added TimaKeyStore provider
V/WindowOrientationListener(  842): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  842): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  842): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  842): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  842): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  842): Display changed displayId=0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/SurfaceWidgetView( 1471): destroyHardwareResources():364087497
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (6/8)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/8)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2058): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1471): onTrimMemory. Level: 20
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7269): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SQLiteSecureOpenHelper( 3579): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3579): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/WebViewFactory( 7269): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 7269): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7269): Loading: webviewchromium
,I/LibraryLoader( 7269): Time to load native libraries: 3 ms (timestamps 4815-4818)
,I/LibraryLoader( 7269): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7269): Binding Chromium to main looper Looper (main, tid 1) {97d96b1}
,I/LibraryLoader( 7269): Expected native library version number "",actual native library version number ""
I/chromium( 7269): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7269): Initializing chromium process, renderers=0
,W/art     ( 7269): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7269): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7269): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 7269): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,I/Adreno-EGL( 7269): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7269): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7269): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7269): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7269): Remote Branch: 
I/Adreno-EGL( 7269): Local Patches: 
I/Adreno-EGL( 7269): Reconstruct Branch: 
,W/chromium( 7269): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/ActivityManager(  842): Activity pause timeout for ActivityRecord{ca48bff u0 com.test.thalitest/.MainActivity t17}
,W/chromium( 7269): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 7269): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 7269): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 7269): CordovaWebView is running on device made by: samsung
,W/art     ( 7269): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7269): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 7269): performCreate Call secproduct feature valuefalse
D/Activity( 7269): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 7269): Render dirty regions requested: true
,D/ActivityManager(  842): post active user change for 0
D/KnoxTimeoutHandler(  842): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  842): handleActiveUserChange for user 0
,I/SurfaceFlinger(  249): id=14 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
,D/StatusBarManagerService(  842): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/StatusBarManagerService(  842): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/OpenGLRenderer( 7269): Initialized EGL, version 1.4
,I/OpenGLRenderer( 7269): HWUI protection enabled for context ,  &this =0xa1553060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 7269): Enabling debug mode 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/InputMethodManagerService(  842): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,W/ActivityManager(  842): mDVFSHelper.release()
I/Timeline(  842): Timeline: Activity_windows_visible id: ActivityRecord{ca48bff u0 com.test.thalitest/.MainActivity t17} time:85451
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/IInputConnectionWrapper( 7269): showStatusIcon on inactive InputConnection
I/Timeline( 7269): Timeline: Activity_idle id: android.os.BinderProxy@f710488 time:85456
E/SMD     (  285): DCD ON
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/chromium( 7269): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7269): 
,D/JsMessageQueue( 7269): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7269): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361693312
,I/chromium( 7269): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/jxcore-log( 7269): Initializing JXcore engine
,W/jxcore-log( 7269): JXcore engine is ready
,E/auditd  ( 2117): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService(  842): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  842): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,W/jxcore-log( 7269): Starting JXcore engine
,E/Zygote  ( 7362): MountEmulatedStorage()
I/libpersona( 7362): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7362): v2
I/libpersona( 7362): KNOX_SDCARD not a persona
,I/ActivityManager(  842): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7362 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7362): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7362): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7362): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7362): TimaSignature is unavailable
,D/ActivityThread( 7362): Added TimaKeyStore provider
,D/ResourcesManager( 7362): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7362):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7362):  SeDenialReceiver : File path = null
,I/ActivityManager(  842): Killing 6473:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,W/jxcore-log( 7269): Platform android
W/jxcore-log( 7269): 
W/jxcore-log( 7269): Process ARCH arm
W/jxcore-log( 7269): 
,W/libprocessgroup(  842): failed to open /acct/uid_10075/pid_6473/cgroup.procs: No such file or directory
,I/jxcore-log( 7269): JXcore Cordova bridge is ready!
I/jxcore-log( 7269): 
,W/jxcore-log( 7269): JXcore engine is started
,E/SMD     (  285): DCD ON
,I/jxcore-log( 7269): Toggling radios to true
I/jxcore-log( 7269): 
,D/BluetoothAdapter( 7269): enable()
,D/BluetoothAdapter( 7269): enable(): BT is already enabled..!
,D/WifiService(  842): New client listening to asynchronous messages
,I/WifiManager( 7269): packageName : com.test.thalitest
,D/SecContentProvider(  842): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  842): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  842): mCursor = null
,D/WifiService(  842): setWifiEnabled: true pid=7269, uid=10200
E/WifiService(  842): Invoking mWifiStateMachine.setWifiEnabled
,W/ActivityManager(  842): Permission Denial: getCurrentUser() from pid=7269, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  842): Failed getting userId using ActivityManagerNative
W/WifiService(  842): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7269, uid=10200 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  842): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  842): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2119)
W/WifiService(  842): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2107)
W/WifiService(  842): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  842): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  842): name = wifi_on
,I/WifiService(  842): disconnect: pid=7269, uid=10200
,I/jxcore-log( 7269): Radios toggled
I/jxcore-log( 7269): 
,I/jxcore-log( 7269): My device name is: samsung-SM-G900F
I/jxcore-log( 7269): 
,I/wpa_supplicant( 1293): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 1293): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1293): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1293): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  842): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1293): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1293): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1293): Disconnected - do not scan
I/wpa_supplicant( 1293): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  842): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  842): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  842): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  842): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  842): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  842): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  842): do suspend true
,D/WifiP2pService(  842): InactiveState{ what=143375 }
,D/WifiP2pService(  842): P2pEnabledState{ what=143375 }
,D/CommandListener(  275): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1638): Read error: ssl=0xaf91ee00: I/O error during system call, Connection timed out
,E/WifiStateMachine(  842): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/ConnectivityService(  842): updateNetworkInfo()
,D/ConnectivityService(  842): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  842): updateNetworkInfo()
,V/NativeCrypto( 1638): SSL shutdown failed: ssl=0xaf91ee00: I/O error during system call, Broken pipe
,D/ConnectivityService(  842): ignoring duplicate network state non-change
D/ConnectivityService(  842): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiConfigStore(  842): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  842): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1293): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1293): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1293): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1293): First Scan Start
,I/wpa_supplicant( 1293): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine(  842): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  842): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine(  842): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  842): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  842): do suspend true
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/WifiTrafficPoller(  842): evaluateTrafficStatsPolling
,D/ConnectivityService(  842): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,I/CLocInfoService(  842): External Intent Received android.net.wifi.STATE_CHANGE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  842): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  842): DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  842): InactiveState{ what=143375 }
D/WifiP2pService(  842): P2pEnabledState{ what=143375 }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  842): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  842): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  842): Validated
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,I/Hs20UtilService( 1304): Starting #6
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,D/CommandListener(  275): Clearing all IP addresses on wlan0
D/ConnectivityService(  842): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity(  842): Not allowed due to - mEnabled false
D/ConnectivityService(  842): calling update connectivity
D/ConnectivityService(  842):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiStateMachine(  842): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/WifiStateMachine(  842): updateConfiguredNetworkExpiration - currTime: 1454433965405
D/ConnectivityService(  842):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/WifiTrafficPoller(  842): evaluateTrafficStatsPolling
D/ConnectivityService(  842): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/WifiStateMachine(  842): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
E/WifiStateMachine(  842): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,D/Nat464Xlat(  842): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  842): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  842): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  842): Disconnected - quitting
E/WifiStateMachine(  842): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/CLocInfoService(  842): External Intent Received android.net.wifi.STATE_CHANGE
D/WifiNetworkAgent(  842): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  842): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524292
E/WifiStateMachine(  842): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  842): setDetailed state send new extra info"NG700"
,D/ConnectivityService(  842): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  842): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1460): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  842): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  842): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  842): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/SecContentProvider2(  842): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  842): mCursor = null
,D/ConnectivityService(  842): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  842): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  842): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
V/NetworkStats(  842): updateIfacesLocked()
D/NtpTrustedTime(  842): currentTimeMillis() cache hit
V/NetworkStats(  842): performPollLocked(flags=0x1)
D/SmartBondingService(  842): getSBEnabled() enabled =false
D/SmartBondingService(  842): getSBEnabled() enabled =false
D/SmartBondingService(  842): getSBEnabled() enabled =false
,D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1171): updateDataNetType()
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
,E/ConnectivityService(  842): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/NetworkStatsFactory(  842): UpdateStatsForKnox
D/NtpTrustedTime(  842): currentTimeMillis() cache hit
D/ConnectivityService(  842): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/SmartBondingService(  842): getNetworkEnabled : wifi : true mobile : true
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
V/NetworkStats(  842): performPollLocked() took 8ms
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
V/NetworkStats(  842): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/NtpTrustedTime(  842): currentTimeMillis() cache hit
D/NtpTrustedTime(  842): currentTimeMillis() cache hit
D/NtpTrustedTime(  842): currentTimeMillis() cache hit
D/NtpTrustedTime(  842): currentTimeMillis() cache hit
,D/SecContentProvider2(  842): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  842): mCursor = null
,D/NtpTrustedTime(  842): currentTimeMillis() cache hit
D/NtpTrustedTime(  842): currentTimeMillis() cache hit
,I/Hs20UtilService( 1304): Starting #7
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1460): FileWriteThread : threadType = 3
,I/PowerManagerService(  842): [PWL] Off : 15s ago
,I/PowerManagerService(  842): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  842): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  842): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=2472, ws=null) (elapsedTime=52742)
,I/PowerManagerService(  842): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=842, ws=null) (elapsedTime=310)
,D/ConnectivityService(  842): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy(  842): updateDataUsageMap
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  842): MasterInitialState.processMessage what=3
,D/SmartBondingService(  842): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  842): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  842): CLoinfo wifi false
,D/SmartBondingService(  842): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  842): getSBEnabled() enabled =false
D/SmartBondingService(  842): getSBEnabled() enabled =false
D/SmartBondingService(  842): getSBEnabled() enabled =false
,W/SLocation(  842): No Active Data Connection
D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 7074): [#DCM#] [DCM_Performance] onReceive completed in time  1486 microsec. 
,I/SystemBroadcastReceiver( 7074): [#DCM#] Calling notifyListeners. 
,I/DCMController( 7074): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7074): [#DCM#] setIsConnectedForExtractors 
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 2058): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  842): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NetworkMonitor( 5350): type=WIFI subType= reason=null isConnected=false
,I/PCWCLIENTTRACE_PushUtil( 6699): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6699): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6699): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6699): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver( 6699): noConnectivity : true
,I/DBG_DM  ( 3780): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3780): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7433): MountEmulatedStorage()
E/Zygote  ( 7433): v2
I/libpersona( 7433): KNOX_SDCARD checking this for 10002
I/libpersona( 7433): KNOX_SDCARD not a persona
I/ActivityManager(  842): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7433 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7433): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7433): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7433): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7433): TimaSignature is unavailable
,D/ActivityThread( 7433): Added TimaKeyStore provider
,D/ResourcesManager( 7433): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  842): Killing 6489:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7450): MountEmulatedStorage()
I/libpersona( 7450): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7450): v2
I/libpersona( 7450): KNOX_SDCARD not a persona
,I/ActivityManager(  842): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7450 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7450): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7450): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7450): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7450): TimaSignature is unavailable
,D/ActivityThread( 7450): Added TimaKeyStore provider
,D/ResourcesManager( 7450): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_6489/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7450): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7450): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7450): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/wpa_supplicant( 1293): nl80211: Received scan results (2 BSSes)
,I/wpa_supplicant( 1293): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1293): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1293): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  842): [1,454,433,966,429 ms] noteScanEnd no scan source
,E/WifiStateMachine(  842): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3882b001 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  842): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  842): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  842): setDetailed state send new extra info0x
,D/SecContentProvider2(  842): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  842): mCursor = null
,I/CLocInfoService(  842): External Intent Received android.net.wifi.SCAN_RESULTS
,I/DIAGMON_AGENT( 7450): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7450): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7450): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 1293): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
E/WifiStateMachine(  842): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  842): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
I/wpa_supplicant( 1293): Associated with C0.AA.48
,E/Zygote  ( 7467): MountEmulatedStorage()
I/libpersona( 7467): KNOX_SDCARD checking this for 10011
E/Zygote  ( 7467): v2
I/libpersona( 7467): KNOX_SDCARD not a persona
D/SecContentProvider2(  842): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  842): mCursor = null
,I/ActivityManager(  842): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7467 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  316): Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 267us total 11.477ms
,I/wpa_supplicant( 1293): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
E/WifiStateMachine(  842): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  842): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  842): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  842): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  842): mCursor = null
,I/wpa_supplicant( 1293): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1293): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 590us total 10.229ms
E/WifiStateMachine(  842): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  842): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/SELinux ( 7467): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/wpa_supplicant( 1293): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1293): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1293): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1293): Blacklist: Clear (temp) 
I/wpa_supplicant( 1293): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
I/SELinux ( 7467): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7467): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/WifiStateMachine(  842): Network connection established
D/WifiNative-HAL(  842): callSECApiVoid - ID [50]
E/WifiStateMachine(  842): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/CLocInfoService(  842): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  842): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 294us total 9.241ms
,D/ConnectivityService(  842): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  842): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  842): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  842): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  842): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService(  842): Got NetworkAgent Messenger
E/ConnectivityService(  842): updateNetworkInfo()
D/ConnectivityService(  842): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  842): NetworkAgent connected
,E/WifiStateMachine(  842): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  842): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  842): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  842): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/TimaKeyStoreProvider( 7467): TimaSignature is unavailable
,D/ActivityThread( 7467): Added TimaKeyStore provider
,D/CommandListener(  275): Setting iface cfg
,E/WifiStateMachine(  842): Start Dhcp Watchdog 2
,D/SecContentProvider2(  842): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  842): mCursor = null
,D/ResourcesManager( 7467): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,E/WifiStateMachine(  842): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  842): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  842): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,I/ActivityManager(  842): Killing 6534:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,I/FOTA_Client( 7467): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7467): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7467): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7467): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7467): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7484): MountEmulatedStorage()
E/Zygote  ( 7484): v2
I/libpersona( 7484): KNOX_SDCARD checking this for 10019
I/libpersona( 7484): KNOX_SDCARD not a persona
,I/ActivityManager(  842): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7484 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  842): Killing 6662:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,E/WifiStateMachine(  842): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  842): do suspend false
,D/SecContentProvider2(  842): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService(  842): InactiveState{ what=143375 }
D/SecContentProvider2(  842): mCursor = null
D/WifiP2pService(  842): P2pEnabledState{ what=143375 }
,I/SELinux ( 7484): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7484): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7484): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_6534/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7484): TimaSignature is unavailable
,D/ActivityThread( 7484): Added TimaKeyStore provider
,D/ResourcesManager( 7484): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,W/libprocessgroup(  842): failed to open /acct/uid_10015/pid_6662/cgroup.procs: No such file or directory
,I/KLMS-2.4.503: ( 7484): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7484): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1454433966757
,I/KLMS-2.4.503: ( 7484): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7484): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7484): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  842): Killing 6681:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7499): MountEmulatedStorage()
E/Zygote  ( 7499): v2
I/libpersona( 7499): KNOX_SDCARD checking this for 10037
I/libpersona( 7499): KNOX_SDCARD not a persona
,I/ActivityManager(  842): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7499 uid=10037 gids={50037, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7499): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7499): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7499): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7499): TimaSignature is unavailable
,D/ActivityThread( 7499): Added TimaKeyStore provider
,D/ResourcesManager( 7499): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7499): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,W/libprocessgroup(  842): failed to open /acct/uid_10016/pid_6681/cgroup.procs: No such file or directory
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/dhcpcd  ( 7517): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7517): version 5.5.6 starting
,E/SPPClientService( 5179): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,E/dhcpcd  ( 7517): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/SA      ( 6737): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6737): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6737): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6737): [SLFUCHKMGR] constructor called
,I/SA      ( 6737): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6737): [OR] == isSIMCardReady false ==
I/SA      ( 6737): [SCU] == networkStateCheck == false
I/SA      ( 6737): [OR] onReceive END
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7517): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7517): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7517): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7517): bssid match
,E/Zygote  ( 7526): MountEmulatedStorage()
,E/Zygote  ( 7526): v2
I/libpersona( 7526): KNOX_SDCARD checking this for 10071
I/libpersona( 7526): KNOX_SDCARD not a persona
,I/ActivityManager(  842): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7526 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,I/dhcpcd  ( 7517): wlan0: rebinding lease of 192.168.1.135
,E/SPPClientService( 5179): [[SystemStateMonitorService]] No Active Internet
,I/SELinux ( 7526): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7526): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/ActivityManager(  842): Killing 6443:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
E/SELinux ( 7526): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7526): TimaSignature is unavailable
,D/ActivityThread( 7526): Added TimaKeyStore provider
,D/ResourcesManager( 7526): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7526): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7526): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7526): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/comsamsunglog( 7526): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7526): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7526): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7526): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7526): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7526): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7526): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7526): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  842): name = aw_daemon_service_key_agree_popup_check
,D/SettingsProvider(  842): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  842): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  842): selectionArgs: false
D/SettingsProvider(  842): selectionArgs: 10071
D/SecContentProvider(  842): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  842): ret = -1
,D/daemonapp( 1380): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/libprocessgroup(  842): failed to open /acct/uid_10034/pid_6443/cgroup.procs: No such file or directory
,D/accuweather( 7526): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7526): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7526): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7526): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7526): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7526): [KK AccuPhone]>>> RM:136 [0:0]  V init 
V/AlarmManager(  842): waitForAlarm result :4
D/daemonapp( 1380): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7526): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1380): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7526): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1380): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7526): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7526): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7548): MountEmulatedStorage()
E/Zygote  ( 7548): v2
I/libpersona( 7548): KNOX_SDCARD checking this for 1000
I/libpersona( 7548): KNOX_SDCARD not a persona
,I/ActivityManager(  842): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7548 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  842): Killing 4707:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
,I/SELinux ( 7548): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/BatteryService(  842): level:100, scale:100, status:2, health:2, present:true, voltage: 4273, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  842): stay LED for charging
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,I/SELinux ( 7548): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7548): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  842): Plugged
I/MotionRecognitionService(  842): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/TimaKeyStoreProvider( 7548): TimaSignature is unavailable
,D/ActivityThread( 7548): Added TimaKeyStore provider
,W/libprocessgroup(  842): failed to open /acct/uid_10035/pid_4707/cgroup.procs: No such file or directory
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/ResourcesManager( 7548): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7548): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7548): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7548): premStatus:2
,I/KnoxUsageLogPro( 7548): isEulaShown : false
I/KnoxUsageLogPro( 7548): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7563): MountEmulatedStorage()
,E/Zygote  ( 7563): v2
I/libpersona( 7563): KNOX_SDCARD checking this for 10088
I/libpersona( 7563): KNOX_SDCARD not a persona
,I/ActivityManager(  842): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7563 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  842): Killing 6002:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
,I/SELinux ( 7563): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7563): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7563): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7563): TimaSignature is unavailable
,D/ActivityThread( 7563): Added TimaKeyStore provider
,D/ResourcesManager( 7563): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/libprocessgroup(  842): failed to open /acct/uid_10042/pid_6002/cgroup.procs: No such file or directory
,I/art     (  842): Explicit concurrent mark sweep GC freed 78349(4MB) AllocSpace objects, 14(289KB) LOS objects, 30% free, 36MB/52MB, paused 1.390ms total 90.722ms
,I/ActivityManager(  842): Killing 5639:com.android.mms/u0a50 (adj 15): bgCount ##41
,D/Headlines( 5488): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5488): getCountryCode(): countryCode = DE
,D/Headlines( 5488): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5488): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5488): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5488): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5488): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,D/HeadlinesCardManager( 5488): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5488): requestUpdateNewsWelcomeCard !!! no welcome card
,E/Zygote  ( 7580): MountEmulatedStorage()
E/Zygote  ( 7580): v2
I/libpersona( 7580): KNOX_SDCARD checking this for 10128
I/libpersona( 7580): KNOX_SDCARD not a persona
,I/ActivityManager(  842): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7580 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7580): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7580): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/CountryDetector(  842): No listener is left
,E/SELinux ( 7580): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7580): TimaSignature is unavailable
,D/ActivityThread( 7580): Added TimaKeyStore provider
,D/ResourcesManager( 7580): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  842): failed to open /acct/uid_10050/pid_5639/cgroup.procs: No such file or directory
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7580): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7580): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7580): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7580): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/WebViewFactory( 7580): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7580): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7580): Loading: webviewchromium
,I/LibraryLoader( 7580): Time to load native libraries: 4 ms (timestamps 1102-1106)
I/LibraryLoader( 7580): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7580): Binding Chromium to main looper Looper (main, tid 1) {3c3d7ad7}
,I/LibraryLoader( 7580): Expected native library version number "",actual native library version number ""
,I/chromium( 7580): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7580): Initializing chromium process, renderers=0
,W/art     ( 7580): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7580): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7580): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 7580): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,W/AudioManagerAndroid( 7580): Requires BLUETOOTH permission
,I/Adreno-EGL( 7580): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7580): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7580): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7580): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7580): Remote Branch: 
I/Adreno-EGL( 7580): Local Patches: 
I/Adreno-EGL( 7580): Reconstruct Branch: 
,I/NSApplication( 7580): Starting up...
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7638): MountEmulatedStorage()
,E/Zygote  ( 7638): v2
I/libpersona( 7638): KNOX_SDCARD checking this for 10138
I/libpersona( 7638): KNOX_SDCARD not a persona
,I/ActivityManager(  842): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7638 uid=10138 gids={50138, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  842): Killing 6759:com.sec.android.app.myfiles/u0a51 (adj 15): bgCount ##41
,I/SELinux ( 7638): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7638): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7638): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 7517): wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,D/TimaKeyStoreProvider( 7638): TimaSignature is unavailable
,D/ActivityThread( 7638): Added TimaKeyStore provider
,V/AlarmManager(  842): waitForAlarm result :4
,I/dhcpcd  ( 7517): wlan0: leased 192.168.1.135 for 86400 seconds
,E/WifiStateMachine(  842): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ResourcesManager( 7638): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
E/WifiStateMachine(  842): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
D/ConnectivityService(  842): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,W/libprocessgroup(  842): failed to open /acct/uid_10051/pid_6759/cgroup.procs: No such file or directory
,W/ResourcesManager( 7638): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7638): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7638): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7638): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7638): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7638): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  842): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7661 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/Zygote  ( 7661): MountEmulatedStorage()
E/Zygote  ( 7661): v2
I/libpersona( 7661): KNOX_SDCARD checking this for 10163
I/libpersona( 7661): KNOX_SDCARD not a persona
,I/ActivityManager(  842): Killing 6780:com.sec.android.app.soundalive/u0a58 (adj 15): bgCount ##41
,E/SMD     (  285): DCD ON
,I/SELinux ( 7661): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7661): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7661): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7661): TimaSignature is unavailable
,D/ActivityThread( 7661): Added TimaKeyStore provider
,D/ResourcesManager( 7661): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7661): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/libprocessgroup(  842): failed to open /acct/uid_10058/pid_6780/cgroup.procs: No such file or directory
,W/ResourcesManager( 7661): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7661): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7661): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManagerService(  842): exchangeData() failure , invalid userId
,D/RCPManagerService(  842): exchangeData() failure , invalid userId
,D/RCPManagerService(  842): exchangeData() failure , invalid userId
,E/WifiStateMachine(  842): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  842): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  842): do suspend true
,D/WifiP2pService(  842): InactiveState{ what=143375 }
D/WifiP2pService(  842): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  842): WifiStateMachine DHCP successful
,E/WifiStateMachine(  842): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  842): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
D/ConnectivityService(  842): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  842): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  842): Not connected state, yet.
E/WifiStateMachine(  842): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiStateMachine(  842): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  842): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  842): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  842): callSECApiInt - ID [210]
,E/WifiStateMachine(  842): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  842): updateNetworkInfo()
,D/ConnectivityService(  842): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  842): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine(  842): updateDnsLinkProperty: enter
I/CLocInfoService(  842): External Intent Received android.net.wifi.STATE_CHANGE
D/WifiWatchdogStateMachine.DnsPinger(  842): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.DnsResolver(  842): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.SingDnsChecker(  842): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  842): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  842): exchangeData() failure , invalid userId
,D/ConnectivityService(  842): Adding Route [fe80::/64 -> :: wlan0] to network 503
E/WifiStateMachine(  842): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/WifiStateMachine(  842): Now, connected state.
E/WifiStateMachine(  842): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
D/ConnectivityService(  842): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/ConnectivityService(  842): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/Zygote  ( 7705): MountEmulatedStorage()
E/ConnectivityService(  842): Unexpected mtu value: 0, wlan0
E/Zygote  ( 7705): v2
D/ConnectivityService(  842): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  842): updateSourceRoutes : add src route for:192.168.1.135
I/libpersona( 7705): KNOX_SDCARD checking this for 10078
I/libpersona( 7705): KNOX_SDCARD not a persona
,V/        (  275): QcRouteController
,I/ActivityManager(  842): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7705 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,E/WifiStateMachine(  842): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,I/WifiTrafficPoller(  842): evaluateTrafficStatsPolling
,I/CLocInfoService(  842): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  842): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,I/WifiTrafficPoller(  842): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  842): mBoosterFLAG : 0
I/WifiTrafficPoller(  842): current booster mode : FullMode
,D/WifiNative-HAL(  842): callSECApiVoid - ID [212]
,I/CLocInfoService(  842): External Intent Received android.net.wifi.STATE_CHANGE
,V/        (  275): QcRouteController
,E/WifiStateMachine(  842): ConnectedState Enter  mScreenOn=false scanperiod=20000
,I/WifiStateMachine(  842): REQUEST_POWER_SAVE_ON
,V/        (  275): QcRouteController
,I/SELinux ( 7705): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/SELinux ( 7705): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/RCPManagerService(  842): exchangeData() failure , invalid userId
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
E/SELinux ( 7705): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
D/RCPManagerService(  842): exchangeData() failure , invalid userId
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
D/TimaKeyStoreProvider( 7705): TimaSignature is unavailable
D/ActivityThread( 7705): Added TimaKeyStore provider
V/        (  275): QcRouteController
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
I/ActivityManager(  842): Killing 6198:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/        (  275): QcRouteController
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/        (  275): QcRouteController
,V/        (  275): QcRouteController
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7362): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7362): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7362): StateMachine : Current State = 1
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
D/SecurityLogAgent( 7362): StateMachine : Changed Current State = 1
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,I/ActivityManager(  842): Killing 6800:com.google.android.apps.docs/u0a98 (adj 15): bgCount ##41
V/        (  275): QcRouteController
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,D/com.peel.receiver.ConnectivityActionReceiver( 1850): ConnectivityActionReceiver onReceive
,D/com.peel.receiver.ConnectivityActionReceiver( 1850): 
D/com.peel.receiver.ConnectivityActionReceiver( 1850): 
D/com.peel.receiver.ConnectivityActionReceiver( 1850): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1850): 
,D/com.peel.receiver.ConnectivityActionReceiver( 1850): NO active network... no services...
,D/com.peel.receiver.ConnectivityActionReceiver( 1850): 
D/com.peel.receiver.ConnectivityActionReceiver( 1850): 
D/com.peel.receiver.ConnectivityActionReceiver( 1850): last run: 1454412206493 -- System.currentTimeMillis()-last_run: 21761958
D/com.peel.receiver.ConnectivityActionReceiver( 1850): ... skip 
D/com.peel.receiver.ConnectivityActionReceiver( 1850): ... skip last_72_check
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,D/ConnectivityService(  842): Setting Dns servers for network 503 to [/192.168.1.1]
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,E/Zygote  ( 7736): MountEmulatedStorage()
E/Zygote  ( 7736): v2
I/libpersona( 7736): KNOX_SDCARD checking this for 10178
I/libpersona( 7736): KNOX_SDCARD not a persona
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,I/ActivityManager(  842): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7736 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/Nat464Xlat(  842): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  842): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService(  842): updateNetworkInfo()
D/ConnectivityService(  842): calling update connectivity
E/ConnectivityService(  842): updateNetworkInfo()
D/ConnectivityService(  842): ignoring duplicate network state non-change
D/ConnectivityService(  842): ignoring duplicate network state non-change
D/ConnectivityService(  842): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  842): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  842): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  842): Connected
D/ConnectivityService(  842): calling update connectivity
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  842): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  842): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  842): Validated
D/ConnectivityService(  842):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  842):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  842):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  842): currentScore = 0, newScore = 60
D/ConnectivityService(  842):    accepting network in place of null
D/ConnectivityService(  842): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  842): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  842): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  842): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
D/ConnectivityService(  842): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  842): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  842): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,V/NetworkStats(  842): updateIfacesLocked()
D/NtpTrustedTime(  842): currentTimeMillis() cache hit
V/NetworkStats(  842): performPollLocked(flags=0x1)
D/NetworkStatsFactory(  842): UpdateStatsForKnox
,D/SmartBondingService(  842): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  842): getSBEnabled() enabled =false
D/SmartBondingService(  842): getSBEnabled() enabled =false
D/SmartBondingService(  842): getSBEnabled() enabled =false
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/EntConnectivity(  842): Not allowed due to - mEnabled false
D/ConnectivityService(  842): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  842): calling update connectivity
D/ConnectivityService(  842):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  842):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  842): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  842): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  842): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  842):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  842):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  842): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  842): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  842): calling update connectivity
D/ConnectivityService(  842):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  842):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  842): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  842): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
V/NetworkStats(  842): performPollLocked() took 7ms
D/NtpTrustedTime(  842): currentTimeMillis() cache hit
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,I/SELinux ( 7736): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/TelephonyNetworkFactory( 1460): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SELinux ( 7736): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
E/SELinux ( 7736): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
V/BitmapFactory( 7661): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524290
,D/SmartBondingService(  842): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1171): updateDataNetType()
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
,D/NtpTrustedTime(  842): currentTimeMillis() cache hit
,D/NtpTrustedTime(  842): currentTimeMillis() cache hit
,D/NtpTrustedTime(  842): currentTimeMillis() cache hit
D/NtpTrustedTime(  842): currentTimeMillis() cache hit
D/NtpTrustedTime(  842): currentTimeMillis() cache hit
,V/NetworkStats(  842): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  842): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_6198/cgroup.procs: No such file or directory
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1171): updateDataNetType()
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
,D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ResourcesManager( 7705): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/TimaKeyStoreProvider( 7736): TimaSignature is unavailable
,D/ActivityThread( 7736): Added TimaKeyStore provider
,D/BadgeProvider( 7705): onCreate
,D/BadgeProvider( 7705): DatabaseHelper
,D/ResourcesManager( 7736): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/BadgeProvider( 7705): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/ActivityManager(  842): Killing 6856:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,D/BadgeProvider( 7705): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7705): sendNotify, [notify] : null
D/BadgeProvider( 7705): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7705): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7705): update, [UpdateCount] : 1
,D/Launcher.Model( 1471): reloadBadges entered.
,W/libprocessgroup(  842): failed to open /acct/uid_10098/pid_6800/cgroup.procs: No such file or directory
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2472): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2472): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7053): notifyNetworkActivated
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup(  842): failed to open /acct/uid_10033/pid_6856/cgroup.procs: No such file or directory
,W/ActivityManager(  842): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ContextImpl( 7053): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  842): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/art     ( 1638): Explicit concurrent mark sweep GC freed 21808(1242KB) AllocSpace objects, 3(243KB) LOS objects, 40% free, 17MB/29MB, paused 512us total 35.567ms
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2472): [AccountUtils] Account not ready
W/Kids    ( 2472): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2472): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2472): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2472): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2472): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2472): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2472): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2472): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2472): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2472): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2472): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2472): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,D/hcjo    ( 7053): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7053): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7053): exit::IDLE
D/InitializeManagerStateMachine( 7053): entry::NETWORK_CHECK
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7053): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7053): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7053): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7053): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7053): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7053): entry::SUCCESS
D/hcjo    ( 7053): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7053): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7053): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
I/Hs20UtilService( 1304): Starting #8
D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Hs20UtilService( 1304): Message received 5007
,D/InitializeManagerStateMachine( 7053): exit::SUCCESS
D/InitializeManagerStateMachine( 7053): entry::IDLE
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7758): MountEmulatedStorage()
,E/Zygote  ( 7758): v2
I/libpersona( 7758): KNOX_SDCARD checking this for 10179
I/libpersona( 7758): KNOX_SDCARD not a persona
,I/ActivityManager(  842): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=7758 uid=10179 gids={50179, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,I/art     (  316): Explicit concurrent mark sweep GC freed 8732(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 276us total 10.412ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.900ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 244us total 7.616ms
,I/SELinux ( 7758): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7758): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7758): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7767): MountEmulatedStorage()
,E/Zygote  ( 7767): v2
I/libpersona( 7767): KNOX_SDCARD checking this for 10082
I/libpersona( 7767): KNOX_SDCARD not a persona
,I/ActivityManager(  842): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7767 uid=10082 gids={50082, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7767): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7767): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/TimaKeyStoreProvider( 7758): TimaSignature is unavailable
,D/ActivityThread( 7758): Added TimaKeyStore provider
,E/SELinux ( 7767): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 7758): creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
,D/TimaKeyStoreProvider( 7767): TimaSignature is unavailable
,D/ActivityThread( 7767): Added TimaKeyStore provider
,W/ResourcesManager( 7758): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/ConnectivityService(  842): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  842): MasterInitialState.processMessage what=3
D/SmartBondingService(  842): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  842): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  842): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  842): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  842): CLocinfo wifi true 
D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  842): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  842): getSBEnabled() enabled =false
D/SmartBondingService(  842): getSBEnabled() enabled =false
D/SmartBondingService(  842): getSBEnabled() enabled =false
,D/SmartBondingService(  842): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7767): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2178): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 2178): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,I/SystemBroadcastReceiver( 7074): [#DCM#] [DCM_Performance] onReceive completed in time  180 microsec. 
,I/SystemBroadcastReceiver( 7074): [#DCM#] Calling notifyListeners. 
D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DCMController( 7074): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
I/DCMController( 7074): [#DCM#] setIsConnectedForExtractors 
D/accuweather( 2058): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5350): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3780): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3780): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DatabaseRebuilderTask( 7074): [#DCM#] postDBrebuildIntent rebuildLocation =  true
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FrameworkService( 7074): [#DCM#] onCreate FrameworkService 
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FrameworkService( 7074): [#DCM#] onCreate FrameworkService end 
,I/DCMConfig( 7074): [#DCM#] getSuccessState = true
I/FrameworkService( 7074): [#DCM#] onStartCommand(intent= Intent { act=com.samsung.dcm.action.DCM_EXECUTE cmp=com.samsung.dcm/.framework.FrameworkService (has extras) }, startId=1
I/IntentHandler( 7074): [#DCM#] Intent action= com.samsung.dcm.action.DCM_EXECUTE, startId=1
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemUtils( 7074): [#DCM#] LM: false,AM:668577792
,I/DCMThreadPoolExecutor( 7074): [#DCM#] Task being added DatabaseRebuilderTask
,I/DCMThreadPoolExecutor( 7074): [#DCM#] Task com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@19b12915 is submitted
I/FrameworkService( 7074): [#DCM#] [DCM_Performance] onStartCommand completed , startId= 1 in time 15851 mirosec. 
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/UMC:Core( 7758): onCreate(): 
,D/USER_AGENT( 7758): UMC/1.1.39 (SM-G900F) SAFE-5.3 KNOX-2.3
,I/ReaderUtils( 7767): PortraitW 1080 LandscapeW 1920 SmallestSize 1005 LargestSize 1920 textZoom 3.3749998 isTablet false Memory 128
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 7767): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ResourcesManager( 1638): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/[SAMSUNG SMARCART NATIVE]( 7758): initialize...
D/[SAMSUNG SMARCART NATIVE]( 7758): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,I/BooksApp( 7767): Created application version: 3.3.11 (30311)
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,I/CSTORAGE( 7758): ================================================
I/CSTORAGE( 7758):  CSTORAGE_SKM_LIB v1.0.8
I/CSTORAGE( 7758): ================================================
,I/TZ_CCM_C_GetFunctionList: ( 7758): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 7758): FINISHED: initialize rv:0
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
D/SecContentProvider2(  842): mCursor = null
,D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/BooksSync( 7767): Starting books sync, d
,D/ResourcesManager( 2472): creating new AssetManager and set to /system/app/Books/Books.apk
,E/HttpOperation( 6549): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6549): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6549): 	at kfv.a(PG:65)
E/HttpOperation( 6549): 	at kff.u(PG:385)
E/HttpOperation( 6549): 	at kfb.a(PG:29)
E/HttpOperation( 6549): 	at kff.l(PG:132)
E/HttpOperation( 6549): 	at dsf.a(PG:807)
E/HttpOperation( 6549): 	at fhk.a(PG:1126)
E/HttpOperation( 6549): 	at fhk.a(PG:908)
E/HttpOperation( 6549): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6549): 	at ihi.a(PG:22)
E/HttpOperation( 6549): 	at kft.a(PG:91)
E/HttpOperation( 6549): 	at kfv.a(PG:62)
E/HttpOperation( 6549): 	... 8 more
E/HttpOperation( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6549): 	at gde.c(Unknown Source)
E/HttpOperation( 6549): 	at gde.b(Unknown Source)
E/HttpOperation( 6549): 	at ihi.a(PG:19)
E/HttpOperation( 6549): 	... 10 more
,D/UMC:SecurityUtils( 7758): Loaded server certificates: 0
,D/UMC:SecurityUtils( 7758): Loaded server certificates: 0
,D/UMC:SecurityUtils( 7758): timaVersion on the device: 3.0
,D/UMC:CloudMDMSecurity( 7758): New Flow
,D/TimaService(  842): TIMA3: in ccmRegisterForDefaultCertificate
D/TimaService(  842): TIMA: in getTimaVersion
,I/        (  842): CCM JNI: In ccm_register_for_default_cert
I/        (  842): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: (  842): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
I/TZ_CCM_C_Initialize: (  842): pInitArgs 0x941ff814 has not called C_Init before.
I/TZ_CCM_C_Initialize: (  842): &ctx = 0x9fa6ec1c
I/TLC_TZ_CCM: (  842): creating new ccm context...
I/TLC_TZ_CCM: (  842): initializing ccm context...
I/TLC_TZ_CCM: (  842): root = /firmware/image, root_strlen = 15
I/TLC_TZ_CCM: (  842): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  842): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  842): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  842): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  842): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  842): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication(  842): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  842): Client_Server_Open was called
I/TZ: client_server_communication(  842): IClientServer::IClientServer()
I/TZ: client_server_communication(  842): BpClientServer::BpClientServer()
I/TZ: client_server_communication(  842): IClientServer::~IClientServer()
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 1078): OPENSWCONN
I/TZ_CCM_SERVER( 1078): creating new ccm context...
I/TZ_CCM_SERVER( 1078): initializing ccm context...
I/TZ_CCM_SERVER( 1078): root = /firmware/image, root_strlen = 15
I/TZ_CCM_SERVER( 1078): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1078): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1078): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1078): aligned max_sendmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1078): aligned max_recvmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1078): max_message_size = 38912 = 0x9800
D/QSEECOMAPI: ( 1078): QSEECom_get_handle sb_length = 0x9800
,D/QSEECOMAPI: ( 1078): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1078): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication( 1078): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
,I/TZ: client_server_communication(  842): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  842): Client_Server_Open succeeded, serverName = CCM
I/TZ_CCM_C_Initialize: (  842): ctx = 0x936debc0, comm = 0x93699700, sendmsg = 0x95ebd000, recvmsg = 0x95ec1c00
I/TZ_init: (  842): TZ_init: sending initialization request...
I/TZ: client_server_communication(  842): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  842): Calling Communicate()
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
,I/TZ_init: (  842): TZ_init: successful initialization
I/TLC_TZ_COMMON: key_db_init: (  842): Exercising TZ_DB_INIT in TLC
,I/TZ: client_server_communication(  842): Cmd id = 17, len = 19456
I/TZ: client_server_communication(  842): Calling Communicate()
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/TZ_COMMON: tlc_key_db_util: (  842): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: (  842): Exercising TZ_CCM_register_default_TLC
I/TZ: client_server_communication(  842): Cmd id = 25, len = 19456
I/TZ: client_server_communication(  842): Calling Communicate()
,I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
,I/TLC_TZ_CCM: register for default cert: (  842): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: (  842): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: (  842): DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
I/TZ: client_server_communication(  842): Cmd id = 41, len = 19456
I/TZ: client_server_communication(  842): Calling Communicate()
I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1078): COMM
,I/TZ: client_server_communication(  842): Client_Server_Close was called
,I/TZ_CCM_SERVER( 1078): BnCCM::onTransact(1) 16
I/TZ_CCM_SERVER( 1078): CLOSESWCONN
D/QSEECOMAPI: ( 1078): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1078): QSEECom_shutdown_app, app_id = 2
,I/TZ: client_server_communication(  842): Client_Server_Close succeeded
D/UMC:CloudMDMSecurity( 7758): ccmRegisterForDefaultCertificate: 0
D/UMC:CloudMDMSecurity( 7758): TIMA service call for password change success!!
,D/UMC:AdminManager( 7758): init - start
,E/SQLiteLog( 7767): (284) automatic index on view_volumes(volume_id)
,D/UMC:AdminManager( 7758): loadAdmins
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
D/SecContentProvider2(  842): mCursor = null
,D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
D/UMC:AdminManager( 7758): startPolicyHandlers
I/UMC:TestPolicyHandler( 7758): Setup is called in testpolicyhandler
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/UMC:AdminManager( 7758): init - end
V/UMC:AlarmHandler( 7758): Enter loadList
,E/HttpOperation( 6549): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6549): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6549): 	at kfv.a(PG:65)
E/HttpOperation( 6549): 	at kff.u(PG:385)
E/HttpOperation( 6549): 	at kfb.a(PG:29)
E/HttpOperation( 6549): 	at kff.l(PG:132)
E/HttpOperation( 6549): 	at ieo.a(PG:43)
E/HttpOperation( 6549): 	at iep.a(PG:93)
E/HttpOperation( 6549): 	at fhn.a(PG:59)
E/HttpOperation( 6549): 	at lex.a(PG:85)
E/HttpOperation( 6549): 	at lex.b(PG:132)
E/HttpOperation( 6549): 	at fhk.a(PG:1146)
E/HttpOperation( 6549): 	at fhk.a(PG:908)
E/HttpOperation( 6549): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6549): 	at ihi.a(PG:22)
E/HttpOperation( 6549): 	at kft.a(PG:91)
E/HttpOperation( 6549): 	at kfv.a(PG:62)
E/HttpOperation( 6549): 	... 12 more
E/HttpOperation( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6549): 	at gde.c(Unknown Source)
E/HttpOperation( 6549): 	at gde.b(Unknown Source)
E/HttpOperation( 6549): 	at ihi.a(PG:19)
E/HttpOperation( 6549): 	... 14 more
,E/ExperimentLoader( 6549): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6549): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6549): 	at kfv.a(PG:65)
E/ExperimentLoader( 6549): 	at kff.u(PG:385)
E/ExperimentLoader( 6549): 	at kfb.a(PG:29)
E/ExperimentLoader( 6549): 	at kff.l(PG:132)
E/ExperimentLoader( 6549): 	at ieo.a(PG:43)
E/ExperimentLoader( 6549): 	at iep.a(PG:93)
E/ExperimentLoader( 6549): 	at fhn.a(PG:59)
E/ExperimentLoader( 6549): 	at lex.a(PG:85)
E/ExperimentLoader( 6549): 	at lex.b(PG:132)
E/ExperimentLoader( 6549): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6549): 	at fhk.a(PG:908)
E/ExperimentLoader( 6549): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6549): 	at ihi.a(PG:22)
E/ExperimentLoader( 6549): 	at kft.a(PG:91)
E/ExperimentLoader( 6549): 	at kfv.a(PG:62)
E/ExperimentLoader( 6549): 	... 12 more
E/ExperimentLoader( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6549): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6549): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6549): 	at ihi.a(PG:19)
E/ExperimentLoader( 6549): 	... 14 more
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/GSLBManager( 7758): migrateStoredUrlFromOldPref
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,D/GSLBManager( 7758): migrateStoredUrlFromOldPref : Migration Not Needed
,D/UMC:UMCAdmin( 7758): deactivateUMCAdminIfNotRequired : -1
,E/UMC:Utils( 7758): Admin not found in package com.samsung.knoxpb.mdm
D/UMC:UMCAdmin( 7758): deactivateUMCAdmin : -1
D/UMC:UMCAdmin( 7758): isContainer : 0
,W/LicenseLogService(  842): log() failed
,D/EnterpriseDeviceManagerService(  842): isManagedProfileUser(): userId = 0
,E/UMC:UMCAdmin( 7758): No active admin owned by uid 10179
,D/UMC:UMCAdmin( 7758): isContainer : 0
,D/UMC:UMCAdmin( 7758): deactivateUMCAdmin - UMC App Admin deactivated
,V/UMC:AlarmHandler( 7758): onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
D/QuickStartReceiver( 7758): Msg Id : 2
D/QuickStartReceiver( 7758): model : SM-G900F
,D/QuickStartReceiver( 7758): id : 100
,I/Hs20UtilService( 1304): Starting #9
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 1304): Message received 5007
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Hs20UtilService( 1304): Starting #10
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1304): Starting #11
,I/Hs20UtilService( 1304): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,D/ConnectivityService(  842): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/WifiStateMachine(  842): callSECApi what=220
D/WifiStateMachine(  842): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1638): creating new AssetManager and set to /system/app/Books/Books.apk
,I/PCWCLIENTTRACE_PushUtil( 6699): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6699): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6699): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6699): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,I/SurfaceFlinger(  249): id=15 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
D/SecContentProvider2(  842): mCursor = null
,D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
I/DIAGMON_AGENT( 7450): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7450): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/PowerManagerService(  842): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=842
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7767): Authentication error
E/BooksAccountManager( 7767): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7767): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7767): null auth token
,I/System.out( 7767): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 7767): (HTTPLog)-Static: isShipBuild true
I/System.out( 7767): (HTTPLog)-Thread-1287-61271503: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6549): [getaccountstatus] Unexpected exception
E/HttpOperation( 6549): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6549): 	at kfv.a(PG:65)
E/HttpOperation( 6549): 	at kff.u(PG:385)
E/HttpOperation( 6549): 	at kfb.a(PG:29)
E/HttpOperation( 6549): 	at ixd.a(PG:248)
E/HttpOperation( 6549): 	at ixd.b(PG:206)
E/HttpOperation( 6549): 	at ixd.a(PG:175)
E/HttpOperation( 6549): 	at fig.a(PG:78)
E/HttpOperation( 6549): 	at lex.a(PG:85)
E/HttpOperation( 6549): 	at lex.b(PG:132)
E/HttpOperation( 6549): 	at fhk.a(PG:1146)
E/HttpOperation( 6549): 	at fhk.a(PG:908)
E/HttpOperation( 6549): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6549): 	at ihi.a(PG:22)
E/HttpOperation( 6549): 	at kft.a(PG:91)
E/HttpOperation( 6549): 	at kfv.a(PG:62)
E/HttpOperation( 6549): 	... 12 more
E/HttpOperation( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6549): 	at gde.c(Unknown Source)
E/HttpOperation( 6549): 	at gde.b(Unknown Source)
E/HttpOperation( 6549): 	at ihi.a(PG:19)
E/HttpOperation( 6549): 	... 14 more
,E/EsSyncAdapterService( 6549): Sync failure
E/EsSyncAdapterService( 6549): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6549): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6549): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6549): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6549): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6549): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6549): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6549): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6549): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6549): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6549): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6549): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6549): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6549): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6549): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6549): 	... 10 more
E/EsSyncAdapterService( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6549): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6549): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6549): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6549): 	... 12 more
E/EsSyncAdapterService( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6549): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6549): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6549): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6549): 	... 14 more
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,D/SyncManager(  842): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 62939, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,I/FOTA_Client( 7467): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7467): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7467): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/FOTA_Client( 7467): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,I/FOTA_Client( 7467): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,I/qtaguid ( 7767): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7767, getuid(): 10082
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/KLMS-2.4.503: ( 7484): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7484): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1454433969636
,I/KLMS-2.4.503: ( 7484): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7484): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7484): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7484): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7484): StateImplV2(): networkChangeListener().END
,I/art     (  842): Explicit concurrent mark sweep GC freed 47579(2MB) AllocSpace objects, 9(469KB) LOS objects, 30% free, 36MB/52MB, paused 1.410ms total 78.903ms
,D/SecContentProvider2(  842): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  842): mCursor = null
,I/SO_AGENT( 7499): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5179): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6737): [OR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6737): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 6737): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6737): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6737): [OR] == isSIMCardReady false ==
D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6737): [SCU] == networkStateCheck == true
I/SA      ( 6737): [DM] getCountryCodeFromCSC : DE
,I/SA      ( 6737): isChinaCountryCode : false
I/SA      ( 6737): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6737): [OR] == networkStateCheck true ==
,I/SA      ( 6737): [OR] GetMyCountryZoneTask
,I/SA      ( 6737): [OR] onReceive END
,I/SA      ( 6737): [SRS] prepareGetMyCountryZone
,I/SA      ( 6737): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6737): [SSP] query invoked
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6737): [TPMU] GetMccFromDB : null
,D/accuweather( 7526): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7526): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
I/SA      ( 6737): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6737): [TPM] isNoProxy(default) : true
,I/KnoxUsageLogPro( 7548): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7548): premStatus:2
,I/KnoxUsageLogPro( 7548): isEulaShown : false
,I/KnoxUsageLogPro( 7548): KnoxUsageReceiver onReceive : not Processible, just return
,D/Headlines( 5488): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5488): getCountryCode(): countryCode = DE
,E/File    ( 6737): fail readDirectory() errno=2
,D/Headlines( 5488): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5488): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5488): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5488): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5488): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5488): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5488): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 7767): Untagging socket 34
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ApiaryClient( 7767): Error response from books API: {
W/ApiaryClient( 7767):  "error": {
W/ApiaryClient( 7767):   "errors": [
W/ApiaryClient( 7767):    {
W/ApiaryClient( 7767):     "domain": "global",
W/ApiaryClient( 7767):     "reason": "required",
W/ApiaryClient( 7767):     "message": "Login Required",
W/ApiaryClient( 7767):     "locationType": "header",
W/ApiaryClient( 7767):     "location": "Authorization"
W/ApiaryClient( 7767):    }
W/ApiaryClient( 7767):   ],
W/ApiaryClient( 7767):   "code": 401,
W/ApiaryClient( 7767):   "message": "Login Required"
W/ApiaryClient( 7767):  }
W/ApiaryClient( 7767): }
,W/ApiaryClient( 7767): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5862369624278546282&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7767): Headers suppressed
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7638): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7638): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7638): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  842): exchangeData() failure , invalid userId
,D/RCPManagerService(  842): exchangeData() failure , invalid userId
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7362): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7362): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7362): StateMachine : Current State = 1
D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7362): StateMachine : Changed Current State = 1
,D/com.peel.receiver.ConnectivityActionReceiver( 1850): ConnectivityActionReceiver onReceive
D/com.peel.receiver.ConnectivityActionReceiver( 1850): 
D/com.peel.receiver.ConnectivityActionReceiver( 1850): 
D/com.peel.receiver.ConnectivityActionReceiver( 1850): country_code: Germany -- rom region: GB
D/com.peel.receiver.ConnectivityActionReceiver( 1850): 
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/com.peel.receiver.ConnectivityActionReceiver( 1850): 
D/com.peel.receiver.ConnectivityActionReceiver( 1850): 
D/com.peel.receiver.ConnectivityActionReceiver( 1850):  network type WIFI path... network offline: false
D/com.peel.receiver.ConnectivityActionReceiver( 1850): 
D/com.peel.receiver.ConnectivityActionReceiver( 1850): has active network... run services...
D/com.peel.receiver.ConnectivityActionReceiver( 1850): 
D/com.peel.receiver.ConnectivityActionReceiver( 1850): 
D/com.peel.receiver.ConnectivityActionReceiver( 1850): last run: 1454412206493 -- System.currentTimeMillis()-last_run: 21763409
D/com.peel.receiver.ConnectivityActionReceiver( 1850): ... skip 
,D/com.peel.receiver.ConnectivityActionReceiver( 1850): ... skip last_72_check
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 7269): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7269): 
,D/ChimeraCfgMgr( 2472): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChimeraCfgMgr( 2472): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7053): AutoUpdateManager:IDLE:execute
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7053): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7053): exit::IDLE
D/InitializeManagerStateMachine( 7053): entry::NETWORK_CHECK
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7053): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7053): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7053): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7053): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7053): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7053): entry::SUCCESS
D/hcjo    ( 7053): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7053): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7053): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7053): exit::SUCCESS
D/InitializeManagerStateMachine( 7053): entry::IDLE
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
D/SecContentProvider2(  842): mCursor = null
,D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/Kids    ( 2472): [AccountUtils] Account not ready
W/Kids    ( 2472): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2472): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2472): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2472): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2472): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2472): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2472): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2472): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2472): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2472): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2472): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2472): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1638): (10) POSIX Error : 11 SQLite Error : 3850
,W/ProcessCpuTracker(  842): Skipping unknown process pid 7670
,W/ProcessCpuTracker(  842): Skipping unknown process pid 7671
,W/ProcessCpuTracker(  842): Skipping unknown process pid 7698
W/ProcessCpuTracker(  842): Skipping unknown process pid 7703
,W/ProcessCpuTracker(  842): Skipping unknown process pid 7824
,I/SA      ( 6737): [RC New] Execute method=[GET] start
,I/SA      ( 6737): [RC New] Security=[true]
,I/System.out( 6737): Thread-1100(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6737): Thread-1100(ApacheHTTPLog):isShipBuild true
,I/System.out( 6737): Thread-1100(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/jxcore-log( 7269): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7269): 
,I/jxcore-log( 7269): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7269): 
,I/jxcore-log( 7269): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 7269): 
,I/jxcore-log( 7269): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7269): 
,D/SSRM:m  (  842): SIOP:: AP = 410, PST = 429, CUR = 300
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  842): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  842): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,D/ConnectivityService(  842): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  842): identical MTU - not setting
,D/ConnectivityService(  842): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  842): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe18:8b78
,V/        (  275): QcRouteController
,E/WifiStateMachine(  842): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService(  842): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/        (  275): QcRouteController
,D/SmartBondingService(  842): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  842): getSBEnabled() enabled =false
D/SmartBondingService(  842): getSBEnabled() enabled =false
,D/SmartBondingService(  842): getSBEnabled() enabled =false
,W/NetworkManagementService(  842): route cmd failed: 
W/NetworkManagementService(  842): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe18:8b78 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  842): '
W/NetworkManagementService(  842): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  842): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  842): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  842): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  842): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  842): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  842): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  842): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:230)
W/NetworkManagementService(  842): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  842): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Nat464Xlat(  842): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  842): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  842): calling update connectivity
,D/ConnectivityService(  842):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  842):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  842): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524295
,D/ConnectivityService(  842): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  842): calling update connectivity
,D/ConnectivityService(  842):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  842):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  842): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524295
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/BooksAccountManager( 7767): Authentication error
E/BooksAccountManager( 7767): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7767): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7767): null auth token
,I/qtaguid ( 7767): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7767, getuid(): 10082
,I/qtaguid ( 7767): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7767, getuid(): 10082
,I/qtaguid ( 7767): Untagging socket 34
W/ApiaryClient( 7767): Error response from books API: {
W/ApiaryClient( 7767):  "error": {
W/ApiaryClient( 7767):   "errors": [
W/ApiaryClient( 7767):    {
W/ApiaryClient( 7767):     "domain": "global",
W/ApiaryClient( 7767):     "reason": "required",
W/ApiaryClient( 7767):     "message": "Login Required",
W/ApiaryClient( 7767):     "locationType": "header",
W/ApiaryClient( 7767):     "location": "Authorization"
W/ApiaryClient( 7767):    }
W/ApiaryClient( 7767):   ],
W/ApiaryClient( 7767):   "code": 401,
W/ApiaryClient( 7767):   "message": "Login Required"
W/ApiaryClient( 7767):  }
W/ApiaryClient( 7767): }
W/ApiaryClient( 7767): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5862369624278546282&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7767): Headers suppressed
D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6737): [RC New] [v2liruge] api execute + 665
I/SA      ( 6737): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6737): AsyncTask #1 calls detatch()
,I/SA      ( 6737): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6737): [OCP] update openData : PL
,I/SA      ( 6737): [TPMU] getNetworkMcc : 
,I/SA      ( 6737): [SCU] saveMccToPreferece Start
,I/SA      ( 6737): [SCU] RegionMCC : 260
I/SA      ( 6737): [SSP] query invoked
,I/SA      ( 6737): [TPMU] GetMccFromDB : null
,I/SA      ( 6737): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6737): [SCU] saveMccToPreferece End
,I/SA      ( 6737): [RC New] executeRequest [v2liruge] end. 727
I/SA      ( 6737): [RC New] Execute end
,I/SA      ( 6737): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6737): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 7517): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :4
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/WifiStateMachine(  842): REQUEST_POWER_SAVE_ON
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/BooksAccountManager( 7767): Authentication error
E/BooksAccountManager( 7767): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7767): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7767): null auth token
,I/qtaguid ( 7767): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7767, getuid(): 10082
,E/WifiStateMachine(  842): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/qtaguid ( 7767): Untagging socket 34
,W/ApiaryClient( 7767): Error response from books API: {
W/ApiaryClient( 7767):  "error": {
W/ApiaryClient( 7767):   "errors": [
W/ApiaryClient( 7767):    {
W/ApiaryClient( 7767):     "domain": "global",
W/ApiaryClient( 7767):     "reason": "required",
W/ApiaryClient( 7767):     "message": "Login Required",
W/ApiaryClient( 7767):     "locationType": "header",
W/ApiaryClient( 7767):     "location": "Authorization"
W/ApiaryClient( 7767):    }
W/ApiaryClient( 7767):   ],
W/ApiaryClient( 7767):   "code": 401,
W/ApiaryClient( 7767):   "message": "Login Required"
W/ApiaryClient( 7767):  }
W/ApiaryClient( 7767): }
,W/ApiaryClient( 7767): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5862369624278546282&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7767): Headers suppressed
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6579): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6579): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6579): [1] 5.onFinished: Scheduling replication attempt 2.
,I/GAV4    ( 7580): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  249): id=15 Removed Toast (8/9)
,I/SurfaceFlinger(  249): id=15 Removed Toast (-2/9)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PowerManagerService(  842): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 842) eventTime = 96325
,D/PowerManagerService(  842): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=842 (0x0)
,D/PowerManagerService(  842): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=842, ws=WorkSource{10059}) (elapsedTime=3471)
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,E/BooksSync( 7767): Soft error
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5862369624278546282&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7767): Headers suppressed
E/BooksSync( 7767): 
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
E/BooksSync( 7767): Sync error
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5862369624278546282&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7767): Headers suppressed
E/BooksSync( 7767): 
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7767): Finished books sync
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  842): Killing 6828:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
,D/SyncManager(  842): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 64128, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  842): failed to open /acct/uid_10099/pid_6828/cgroup.procs: No such file or directory
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  842): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  842): mCursor = null
,E/SMD     (  285): DCD ON
,I/GAV2    ( 7767): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6699): mConnectivityHandler : connected
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6699): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6699): ================================================
I/CSTORAGE( 6699):  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
I/CSTORAGE( 6699): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6699): [GetString-S]
E/art     ( 6699): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 6699): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6699): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6699): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6699): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6699): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6699): [ensureRegistration] - No Samsung account
,V/AlarmManager(  842): waitForAlarm result :4
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1638): Connected
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1638): Message class com.google.f.a.a.p
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/dhcpcd  ( 7517): wlan0: sending IPv6 Router Solicitation
,I/jxcore-log( 7269): Test app app.js loaded
I/jxcore-log( 7269): 
,I/chromium( 7269): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7269): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7269): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7269): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7269): 	Bluetooth MAC address: B0:C5:59:3F:75:69, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7269): 	Discovery mode: BLE_AND_WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7269): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7269): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7269): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7269): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7269): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@139cf0e9 added. We now have 1 listener(s)
,I/jxcore-log( 7269): BLE advertisement is supported
I/jxcore-log( 7269): 
,E/SMD     (  285): DCD ON
,D/PreloadUpdateManagerStateMachine( 7053): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7053): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7053): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7053): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7053): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7053): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7053): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7053): entry::IDLE
,I/dhcpcd  ( 7517): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7517): wlan0: no IPv6 Routers available
,D/PackageManager(  842): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  842): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  842): Reconfiguring input devices.  changes=0x00000010
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7878): MountEmulatedStorage()
,I/ActivityManager(  842): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7878 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/Zygote  ( 7878): v2
I/libpersona( 7878): KNOX_SDCARD checking this for 10034
I/libpersona( 7878): KNOX_SDCARD not a persona
,D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/SELinux ( 7878): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7878): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,E/SELinux ( 7878): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RegisteredServicesCache( 1454): empty dynamic service
,D/ResourcesManager( 1471): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 1471): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1471): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1471): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/TimaKeyStoreProvider( 7878): TimaSignature is unavailable
,D/ResourcesManager( 1471): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
D/ActivityThread( 7878): Added TimaKeyStore provider
,W/ResourcesManager( 1471): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1471): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Books/Books.apk
,D/SecContentProvider2(  842): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  842): mCursor = null
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/FeatureConfig( 7878): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/BackupManagerService(  842): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  842): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  842): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  842): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 7878): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 7878): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 7878): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/PreloadUpdateManagerStateMachine( 7053): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 7053): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7053): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7053): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 7053): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7053): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7053): entry::IDLE
D/PreloadUpdateManagerStateMachine( 7053): execute::IDLE:CHECK_TIMER_OVER
,W/ResourcesManager( 7878): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 7878): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 7878): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7878): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7878): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7878): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7878): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7878): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7878): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 7878): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7878): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7878): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7878): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7878): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7878): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7916): MountEmulatedStorage()
,I/libpersona( 7916): KNOX_SDCARD checking this for 10035
E/Zygote  ( 7916): v2
I/libpersona( 7916): KNOX_SDCARD not a persona,
,I/ActivityManager(  842): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=7916 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  842): Killing 6897:com.sec.android.provider.logsprovider/u0a20 (adj 15): bgCount ##41
,E/Watchdog(  842): !@Sync 3
,I/SELinux ( 7916): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7916): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7916): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  842): failed to open /acct/uid_10020/pid_6897/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7916): TimaSignature is unavailable
,D/ActivityThread( 7916): Added TimaKeyStore provider
,E/SMD     (  285): DCD ON
D/ResourcesManager( 7916): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7938): MountEmulatedStorage()
E/Zygote  ( 7938): v2
I/libpersona( 7938): KNOX_SDCARD checking this for 10017
I/libpersona( 7938): KNOX_SDCARD not a persona
,I/SELinux ( 7938): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7938): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7938): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  842): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=7938 uid=10017 gids={50017, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 7938): TimaSignature is unavailable
,D/ActivityThread( 7938): Added TimaKeyStore provider
,D/ResourcesManager( 7938): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/BluetoothManager( 7916): getConnectedDevices
,I/SecureStorage( 7938): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  360): [INFO]: SPID(0x00000005)Credentials: uid 10017, gid 10017, pid 7938
I/SecureStorage(  360): [INFO]: SPID(0x00000005)Received function mask & code: 0x00000106
,D/-----SIC-----( 7916): ------------------skip uv
,D/-----SIC-----( 7916): ------------------skip SPO2
D/-----SIC-----( 7916): ------------------skip TGH
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7916): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7916): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
,V/MediaPlayer( 7916): decode(32, 19359868, 4230)
,V/MediaPlayerService(  290): decode(30, 19359868, 4230)
,V/MediaPlayerService(  290): player type = 3
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): constructor
,V/AwesomePlayer(  290): setDefault
,V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
,V/StagefrightPlayer(  290): StagefrightPlayer
V/AwesomePlayer(  290): setListener
V/StagefrightPlayer(  290): initCheck
V/AwesomePlayer(  290): setAudioSink
V/StagefrightPlayer(  290): setDataSource(30, 19359868, 4230)
V/AwesomePlayer(  290): reset_l()
,V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
,V/AwesomePlayer(  290): mSecMediaClock clear
D/Utils   (  290): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  290): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  290): mBitrate = -1 bits/sec
I/OggExtractor(  290): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  290): current audio track index (0) is added to vector
V/AwesomePlayer(  290): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  290): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  290): prepare
,V/AwesomePlayer(  290): prepareAsync
,V/MediaPlayerService(  290): wait for prepare
,V/AwesomePlayer(  290): onPrepareAsyncEvent
,I/SecMediaClock(  290): SecMediaClock constructor
I/SecMediaClock(  290): reset
I/SecVideoCapture(  290): SecVideoCapture constructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): initAudioDecoder
,V/AwesomePlayer(  290): checkOffloadExceptions is true
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  290): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  290): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  290): finishAsyncPrepare_l
V/AwesomePlayer(  290): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache(  290): notify(0xb1558150, 200, 973, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 5, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache(  290): notify(0xb1558150, 1, 0, 0)
V/AudioCache(  290): prepared
V/AudioCache(  290): wait - success
V/MediaPlayerService(  290): start
V/StagefrightPlayer(  290): start
V/AwesomePlayer(  290): play
,V/AwesomePlayer(  290): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  290): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  290): start of Playback, useOffload 0
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer(  290): Audio channels(1)
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  290): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  290): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,I/AudioPlayer(  290): First fillBuffer call!!
V/AudioCache(  290): notify(0xb1558150, 6, 0, 0)
I/AudioPlayer(  290): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  290): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): postAudioEOS delayUs (0)
V/AwesomePlayer(  290): addBatteryData
,V/MediaPlayerService(  290): wait for playback complete
V/AwesomePlayer(  290): onCheckAudioStatus
V/AwesomePlayer(  290): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  290): onStreamDone
V/AwesomePlayer(  290): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  290): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
,V/AudioCache(  290): notify(0xb1558150, 2, 0, 0)
V/AudioCache(  290): playback complete - thread will wake up later
V/AwesomePlayer(  290): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  290): notify(0xb1558150, 7, 0, 0)
,V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  290): addBatteryData
,V/AudioCache(  290): wait - success
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
D/AudioPlayer(  290): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop() sendCommand(0x74, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  290): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  290): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  290): ~OggSource --
I/OggExtractor(  290): ~OggExtractor ++
I/OggExtractor(  290): ~MyVorbisExtractor ++ 
I/OggExtractor(  290): ~MyVorbisExtractor --
I/OggExtractor(  290): ~OggExtractor --
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthServiceInstalled() : HealthService is Installed.
,I/AudioPlayer(  290): reset out
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  290): SecVideoCapture destructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): mSecCapture clear
I/SecMediaClock(  290): SecMediaClock destructor
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): ~StagefrightPlayer
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/AwesomePlayer(  290): destructor
D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/MediaPlayer( 7916): decode(35, 19213040, 15440)
V/MediaPlayerService(  290): decode(30, 19213040, 15440)
,V/MediaPlayerService(  290): player type = 3
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): constructor
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): StagefrightPlayer
V/AwesomePlayer(  290): setListener
V/StagefrightPlayer(  290): initCheck
V/AwesomePlayer(  290): setAudioSink
V/StagefrightPlayer(  290): setDataSource(30, 19213040, 15440)
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
D/Utils   (  290): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  290): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  290): mBitrate = -1 bits/sec
I/OggExtractor(  290): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  290): current audio track index (0) is added to vector
V/AwesomePlayer(  290): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  290): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  290): prepare
V/AwesomePlayer(  290): prepareAsync
V/MediaPlayerService(  290): wait for prepare
,V/AwesomePlayer(  290): onPrepareAsyncEvent
I/SecMediaClock(  290): SecMediaClock constructor
I/SecMediaClock(  290): reset
I/SecVideoCapture(  290): SecVideoCapture constructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): initAudioDecoder
V/AwesomePlayer(  290): checkOffloadExceptions is true
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  290): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  290): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  290): finishAsyncPrepare_l
V/AwesomePlayer(  290): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 200, 973, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 5, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 1, 0, 0)
V/AudioCache(  290): prepared
V/AudioCache(  290): wait - success
V/MediaPlayerService(  290): start
V/StagefrightPlayer(  290): start
V/AwesomePlayer(  290): play
V/AwesomePlayer(  290): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  290): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  290): start of Playback, useOffload 0
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  290): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  290): Audio channels(2)
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/ActivityManager(  842): Killing 6891:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  290): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  290): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 6, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): addBatteryData
V/MediaPlayerService(  290): wait for playback complete
D/AdaptiveEventManager( 1171): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
,D/AdaptiveEventManager( 1171): M updateContainers()
D/AdaptiveEventContainerSmall( 1171): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1171): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1171): pedoEvent == null
,I/AudioPlayer(  290): First fillBuffer call!!
,I/AudioPlayer(  290): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  290): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,D/AdaptiveEventManager( 1171): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
,D/AdaptiveEventManager( 1171): M updateContainers()
D/AdaptiveEventContainerSmall( 1171): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1171): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1171): pedoEvent == null
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] End Of Stream
,I/UpdateIcingCorporaServi( 1547): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,E/DatabaseUtils(  842): Writing exception to parcel
E/DatabaseUtils(  842): java.lang.NullPointerException: key == null
E/DatabaseUtils(  842): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  842): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  842): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  842): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  842): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  842): 	at android.os.Binder.execTransact(Binder.java:446)
V/AwesomePlayer(  290): postAudioEOS delayUs (0)
V/AwesomePlayer(  290): onCheckAudioStatus
V/AwesomePlayer(  290): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  290): onStreamDone
V/AwesomePlayer(  290): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  290): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 2, 0, 0)
V/AudioCache(  290): playback complete - thread will wake up later
V/AwesomePlayer(  290): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 7, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  290): addBatteryData
V/AudioCache(  290): wait - success
V/StagefrightPlayer(  290): reset
,V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
D/AudioPlayer(  290): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop() sendCommand(0x75, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  290): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  290): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  290): ~OggSource --
I/OggExtractor(  290): ~OggExtractor ++
I/OggExtractor(  290): ~MyVorbisExtractor ++ 
I/OggExtractor(  290): ~MyVorbisExtractor --
I/OggExtractor(  290): ~OggExtractor --
,I/AudioPlayer(  290): reset out
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  290): SecVideoCapture destructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): mSecCapture clear
I/SecMediaClock(  290): SecMediaClock destructor
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): ~StagefrightPlayer
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/AwesomePlayer(  290): destructor
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/MediaPlayer( 7916): decode(36, 19257568, 9226)
V/MediaPlayerService(  290): decode(30, 19257568, 9226)
,V/MediaPlayerService(  290): player type = 3
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): constructor
,V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): StagefrightPlayer
V/AwesomePlayer(  290): setListener
V/StagefrightPlayer(  290): initCheck
V/AwesomePlayer(  290): setAudioSink
V/StagefrightPlayer(  290): setDataSource(30, 19257568, 9226)
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
D/Utils   (  290): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  290): track of type 'audio/vorbis' does not publish bitrate
I/libpersona( 7988): KNOX_SDCARD checking this for 10075
V/AwesomePlayer(  290): mBitrate = -1 bits/sec
I/libpersona( 7988): KNOX_SDCARD not a persona
I/OggExtractor(  290): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  290): current audio track index (0) is added to vector
V/AwesomePlayer(  290): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  290): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  290): prepare
V/AwesomePlayer(  290): prepareAsync
V/MediaPlayerService(  290): wait for prepare
V/AwesomePlayer(  290): onPrepareAsyncEvent
I/SecMediaClock(  290): SecMediaClock constructor
I/SecMediaClock(  290): reset
I/SecVideoCapture(  290): SecVideoCapture constructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): initAudioDecoder
V/AwesomePlayer(  290): checkOffloadExceptions is true
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
E/Zygote  ( 7988): MountEmulatedStorage()
E/Zygote  ( 7988): v2
I/OMXCodec(  290): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  290): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  290): finishAsyncPrepare_l
V/AwesomePlayer(  290): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 200, 973, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 5, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 1, 0, 0)
V/AudioCache(  290): prepared
V/AudioCache(  290): wait - success
V/MediaPlayerService(  290): start
V/StagefrightPlayer(  290): start
V/AwesomePlayer(  290): play
V/AwesomePlayer(  290): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  290): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  290): start of Playback, useOffload 0
I/OMXCodec(  290): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  290): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  290): Audio channels(2)
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  290): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  290): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 6, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): addBatteryData
V/MediaPlayerService(  290): wait for playback complete
,I/ActivityManager(  842): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7988 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  842): waitForAlarm result :4
I/AudioPlayer(  290): First fillBuffer call!!
I/AudioPlayer(  290): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  290): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,I/SELinux ( 7988): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7988): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7988): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  290): postAudioEOS delayUs (0)
,V/AwesomePlayer(  290): onCheckAudioStatus
V/AwesomePlayer(  290): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  290): onStreamDone
V/AwesomePlayer(  290): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  290): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 2, 0, 0)
V/AudioCache(  290): playback complete - thread will wake up later
V/AwesomePlayer(  290): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 7, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  290): addBatteryData
V/AudioCache(  290): wait - success
V/StagefrightPlayer(  290): reset
,V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
D/AudioPlayer(  290): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop() sendCommand(0x76, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  290): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  290): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  290): ~OggSource --
I/OggExtractor(  290): ~OggExtractor ++
I/OggExtractor(  290): ~MyVorbisExtractor ++ 
I/OggExtractor(  290): ~MyVorbisExtractor --
I/OggExtractor(  290): ~OggExtractor --
,I/ActivityManager(  842): Killing 6925:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,I/AudioPlayer(  290): reset out
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  290): SecVideoCapture destructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): mSecCapture clear
I/SecMediaClock(  290): SecMediaClock destructor
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): ~StagefrightPlayer
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/AwesomePlayer(  290): destructor
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/MediaPlayer( 7916): decode(37, 19364180, 4890)
V/MediaPlayerService(  290): decode(30, 19364180, 4890)
,V/MediaPlayerService(  290): player type = 3
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): constructor
,V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): StagefrightPlayer
V/AwesomePlayer(  290): setListener
V/StagefrightPlayer(  290): initCheck
V/AwesomePlayer(  290): setAudioSink
V/StagefrightPlayer(  290): setDataSource(30, 19364180, 4890)
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
D/Utils   (  290): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  290): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  290): mBitrate = -1 bits/sec
I/OggExtractor(  290): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  290): current audio track index (0) is added to vector
V/AwesomePlayer(  290): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  290): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  290): prepare
V/AwesomePlayer(  290): prepareAsync
V/MediaPlayerService(  290): wait for prepare
V/AwesomePlayer(  290): onPrepareAsyncEvent
I/SecMediaClock(  290): SecMediaClock constructor
I/SecMediaClock(  290): reset
I/SecVideoCapture(  290): SecVideoCapture constructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): initAudioDecoder
V/AwesomePlayer(  290): checkOffloadExceptions is true
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  290): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  290): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  290): finishAsyncPrepare_l
V/AwesomePlayer(  290): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 200, 973, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 5, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 1, 0, 0)
V/AudioCache(  290): prepared
V/AudioCache(  290): wait - success
V/MediaPlayerService(  290): start
V/StagefrightPlayer(  290): start
V/AwesomePlayer(  290): play
V/AwesomePlayer(  290): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  290): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  290): start of Playback, useOffload 0
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  290): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  290): Audio channels(1)
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  290): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  290): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 6, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): addBatteryData
I/AudioPlayer(  290): First fillBuffer call!!
I/AudioPlayer(  290): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  290): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/MediaPlayerService(  290): wait for playback complete
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  290): postAudioEOS delayUs (0)
V/AwesomePlayer(  290): onCheckAudioStatus
V/AwesomePlayer(  290): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  290): onStreamDone
V/AwesomePlayer(  290): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  290): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 2, 0, 0)
V/AudioCache(  290): playback complete - thread will wake up later
V/AwesomePlayer(  290): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 7, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  290): addBatteryData
V/AudioCache(  290): wait - success
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
D/AudioPlayer(  290): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop() sendCommand(0x77, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  290): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  290): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  290): ~OggSource --
I/OggExtractor(  290): ~OggExtractor ++
I/OggExtractor(  290): ~MyVorbisExtractor ++ 
I/OggExtractor(  290): ~MyVorbisExtractor --
I/OggExtractor(  290): ~OggExtractor --
,I/AudioPlayer(  290): reset out
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  290): SecVideoCapture destructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): mSecCapture clear
I/SecMediaClock(  290): SecMediaClock destructor
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): ~StagefrightPlayer
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/AwesomePlayer(  290): destructor
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/MediaPlayer( 7916): decode(38, 19290344, 17329)
V/MediaPlayerService(  290): decode(30, 19290344, 17329)
,V/MediaPlayerService(  290): player type = 3
D/TimaKeyStoreProvider( 7988): TimaSignature is unavailable
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): constructor
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): StagefrightPlayer
V/AwesomePlayer(  290): setListener
V/StagefrightPlayer(  290): initCheck
V/AwesomePlayer(  290): setAudioSink
V/StagefrightPlayer(  290): setDataSource(30, 19290344, 17329)
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
D/Utils   (  290): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ActivityThread( 7988): Added TimaKeyStore provider
,V/AwesomePlayer(  290): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  290): mBitrate = -1 bits/sec
I/OggExtractor(  290): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  290): current audio track index (0) is added to vector
V/AwesomePlayer(  290): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  290): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  290): prepare
V/AwesomePlayer(  290): prepareAsync
V/MediaPlayerService(  290): wait for prepare
V/AwesomePlayer(  290): onPrepareAsyncEvent
I/SecMediaClock(  290): SecMediaClock constructor
I/SecMediaClock(  290): reset
I/SecVideoCapture(  290): SecVideoCapture constructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): initAudioDecoder
V/AwesomePlayer(  290): checkOffloadExceptions is true
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,D/BatteryService(  842): level:100, scale:100, status:2, health:2, present:true, voltage: 4317, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  842): stay LED for charging
,I/OMXCodec(  290): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  290): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  842): Plugged
I/MotionRecognitionService(  842): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  290): finishAsyncPrepare_l
V/AwesomePlayer(  290): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 200, 973, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 5, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 1, 0, 0)
V/AudioCache(  290): prepared
V/AudioCache(  290): wait - success
V/MediaPlayerService(  290): start
V/StagefrightPlayer(  290): start
V/AwesomePlayer(  290): play
V/AwesomePlayer(  290): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  290): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  290): start of Playback, useOffload 0
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  290): Audio channels(2)
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache(  290): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  290): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  290): notify(0xb0924c90, 6, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): addBatteryData
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/MediaPlayerService(  290): wait for playback complete
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
I/AudioPlayer(  290): First fillBuffer call!!
I/AudioPlayer(  290): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  290): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,W/libprocessgroup(  842): failed to open /acct/uid_10003/pid_6891/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1547): UpdateCorporaTask done [took 119 ms] updated apps [took 119 ms] 
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] End Of Stream
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
V/AwesomePlayer(  290): postAudioEOS delayUs (0)
V/AwesomePlayer(  290): onCheckAudioStatus
V/AwesomePlayer(  290): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  290): onStreamDone
V/AwesomePlayer(  290): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  290): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 2, 0, 0)
V/AudioCache(  290): playback complete - thread will wake up later
V/AwesomePlayer(  290): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 7, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  290): addBatteryData
V/AudioCache(  290): wait - success
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
D/AudioPlayer(  290): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop() sendCommand(0x78, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  290): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  290): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  290): ~OggSource --
I/OggExtractor(  290): ~OggExtractor ++
I/OggExtractor(  290): ~MyVorbisExtractor ++ 
I/OggExtractor(  290): ~MyVorbisExtractor --
I/OggExtractor(  290): ~OggExtractor --
,D/ResourcesManager( 7988): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,I/AudioPlayer(  290): reset out
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  290): SecVideoCapture destructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): mSecCapture clear
I/SecMediaClock(  290): SecMediaClock destructor
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): ~StagefrightPlayer
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/AwesomePlayer(  290): destructor
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/MediaPlayer( 7916): decode(39, 19190536, 6644)
,V/MediaPlayerService(  290): decode(30, 19190536, 6644)
,V/MediaPlayerService(  290): player type = 3
,V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): constructor
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): StagefrightPlayer
V/AwesomePlayer(  290): setListener
V/StagefrightPlayer(  290): initCheck
V/AwesomePlayer(  290): setAudioSink
V/StagefrightPlayer(  290): setDataSource(30, 19190536, 6644)
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
D/Utils   (  290): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  290): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  290): mBitrate = -1 bits/sec
I/OggExtractor(  290): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  290): current audio track index (0) is added to vector
V/AwesomePlayer(  290): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  290): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  290): prepare
V/AwesomePlayer(  290): prepareAsync
V/MediaPlayerService(  290): wait for prepare
V/AwesomePlayer(  290): onPrepareAsyncEvent
I/SecMediaClock(  290): SecMediaClock constructor
I/SecMediaClock(  290): reset
I/SecVideoCapture(  290): SecVideoCapture constructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): initAudioDecoder
V/AwesomePlayer(  290): checkOffloadExceptions is true
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  290): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  290): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  290): finishAsyncPrepare_l
V/AwesomePlayer(  290): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 200, 973, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 5, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 1, 0, 0)
V/AudioCache(  290): prepared
V/AudioCache(  290): wait - success
V/MediaPlayerService(  290): start
V/StagefrightPlayer(  290): start
V/AwesomePlayer(  290): play
V/AwesomePlayer(  290): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  290): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  290): start of Playback, useOffload 0
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  290): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  290): Audio channels(1)
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  290): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  290): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 6, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): addBatteryData
I/AudioPlayer(  290): First fillBuffer call!!
I/AudioPlayer(  290): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  290): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,V/MediaPlayerService(  290): wait for playback complete
,W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_6925/cgroup.procs: No such file or directory
,D/FileShare-Server( 7988): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  290): postAudioEOS delayUs (0)
V/AwesomePlayer(  290): onCheckAudioStatus
V/AwesomePlayer(  290): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  290): onStreamDone
V/AwesomePlayer(  290): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  290): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 2, 0, 0)
V/AudioCache(  290): playback complete - thread will wake up later
V/AwesomePlayer(  290): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 7, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  290): addBatteryData
,V/AudioCache(  290): wait - success
V/StagefrightPlayer(  290): reset
,V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
D/AudioPlayer(  290): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop mState=4
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop() sendCommand(0x79, OMX_CommandStateSet, OMX_StateIdle)
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  290): OggSource::stop() mExtractor ref count = 1
,I/OggExtractor(  290): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  290): ~OggSource --
I/OggExtractor(  290): ~OggExtractor ++
I/OggExtractor(  290): ~MyVorbisExtractor ++ 
I/OggExtractor(  290): ~MyVorbisExtractor --
,I/OggExtractor(  290): ~OggExtractor --
,I/AudioPlayer(  290): reset out
,V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  290): SecVideoCapture destructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): mSecCapture clear
I/SecMediaClock(  290): SecMediaClock destructor
V/AwesomePlayer(  290): mSecMediaClock clear
,V/StagefrightPlayer(  290): ~StagefrightPlayer
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
,V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/AwesomePlayer(  290): destructor
,V/AwesomePlayer(  290): reset_l()
,V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/MediaPlayer( 7916): decode(40, 19266876, 23389)
,V/MediaPlayerService(  290): decode(30, 19266876, 23389)
,V/MediaPlayerService(  290): player type = 3
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): constructor
,V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): StagefrightPlayer
V/AwesomePlayer(  290): setListener
V/StagefrightPlayer(  290): initCheck
V/AwesomePlayer(  290): setAudioSink
V/StagefrightPlayer(  290): setDataSource(30, 19266876, 23389)
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
D/Utils   (  290): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  290): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer(  290): mBitrate = -1 bits/sec
I/OggExtractor(  290): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  290): current audio track index (0) is added to vector
V/AwesomePlayer(  290): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  290): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  290): prepare
,V/AwesomePlayer(  290): prepareAsync
V/MediaPlayerService(  290): wait for prepare
I/PowerManagerService(  842): [PWL] Off : 30s ago
I/PowerManagerService(  842): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  842): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  842): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=842, ws=WorkSource{10012}) (elapsedTime=137)
,V/AwesomePlayer(  290): onPrepareAsyncEvent
I/SecMediaClock(  290): SecMediaClock constructor
I/SecMediaClock(  290): reset
I/SecVideoCapture(  290): SecVideoCapture constructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): initAudioDecoder
,V/AwesomePlayer(  290): checkOffloadExceptions is true
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  290): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  290): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  290): finishAsyncPrepare_l
V/AwesomePlayer(  290): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
E/Zygote  ( 8022): MountEmulatedStorage()
E/Zygote  ( 8022): v2
I/libpersona( 8022): KNOX_SDCARD checking this for 1000
I/libpersona( 8022): KNOX_SDCARD not a persona
,V/AudioCache(  290): notify(0xb0924ba0, 200, 973, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
I/ActivityManager(  842): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=8022 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
V/AudioCache(  290): notify(0xb0924ba0, 5, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 1, 0, 0)
,V/AudioCache(  290): prepared
V/AudioCache(  290): wait - success
I/ActivityManager(  842): Killing 6945:com.samsung.android.app.watchmanagerstub/u0a112 (adj 15): bgCount ##41
V/MediaPlayerService(  290): start
V/StagefrightPlayer(  290): start
,V/AwesomePlayer(  290): play
,V/AwesomePlayer(  290): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  290): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  290): start of Playback, useOffload 0
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  290): Audio channels(2)
,I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  290): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  290): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 6, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): addBatteryData
V/MediaPlayerService(  290): wait for playback complete
,D/SSRM:m  (  842): SIOP:: AP = 400, PST = 426, CUR = 300
,I/SELinux ( 8022): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/AudioPlayer(  290): First fillBuffer call!!
I/AudioPlayer(  290): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  290): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/SELinux ( 8022): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8022): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  290): postAudioEOS delayUs (0)
V/AwesomePlayer(  290): onCheckAudioStatus
V/AwesomePlayer(  290): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  290): onStreamDone
V/AwesomePlayer(  290): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  290): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 2, 0, 0)
V/AudioCache(  290): playback complete - thread will wake up later
V/AwesomePlayer(  290): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 7, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  290): addBatteryData
V/AudioCache(  290): wait - success
V/StagefrightPlayer(  290): reset
,V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
D/AudioPlayer(  290): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop() sendCommand(0x7a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,D/TimaKeyStoreProvider( 8022): TimaSignature is unavailable
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  290): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  290): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  290): ~OggSource --
I/OggExtractor(  290): ~OggExtractor ++
I/OggExtractor(  290): ~MyVorbisExtractor ++ 
I/OggExtractor(  290): ~MyVorbisExtractor --
I/OggExtractor(  290): ~OggExtractor --
,D/ActivityThread( 8022): Added TimaKeyStore provider
,I/AudioPlayer(  290): reset out
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  290): SecVideoCapture destructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): mSecCapture clear
I/SecMediaClock(  290): SecMediaClock destructor
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): ~StagefrightPlayer
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/AwesomePlayer(  290): destructor
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/MediaPlayer( 7916): decode(41, 19156232, 8154)
,V/MediaPlayerService(  290): decode(30, 19156232, 8154)
,V/MediaPlayerService(  290): player type = 3
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): constructor
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): StagefrightPlayer
V/AwesomePlayer(  290): setListener
V/StagefrightPlayer(  290): initCheck
V/AwesomePlayer(  290): setAudioSink
V/StagefrightPlayer(  290): setDataSource(30, 19156232, 8154)
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
D/Utils   (  290): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  290): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  290): mBitrate = -1 bits/sec
I/OggExtractor(  290): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  290): current audio track index (0) is added to vector
V/AwesomePlayer(  290): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  290): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  290): prepare
V/AwesomePlayer(  290): prepareAsync
V/MediaPlayerService(  290): wait for prepare
,V/AwesomePlayer(  290): onPrepareAsyncEvent
I/SecMediaClock(  290): SecMediaClock constructor
I/SecMediaClock(  290): reset
I/SecVideoCapture(  290): SecVideoCapture constructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): initAudioDecoder
V/AwesomePlayer(  290): checkOffloadExceptions is true
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  290): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  290): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  290): finishAsyncPrepare_l
V/AwesomePlayer(  290): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 200, 973, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 5, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 1, 0, 0)
V/AudioCache(  290): prepared
V/AudioCache(  290): wait - success
V/MediaPlayerService(  290): start
V/StagefrightPlayer(  290): start
,V/AwesomePlayer(  290): play
V/AwesomePlayer(  290): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  290): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  290): start of Playback, useOffload 0
,D/ResourcesManager( 8022): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  290): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  290): Audio channels(1)
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  290): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  290): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 6, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): addBatteryData
V/MediaPlayerService(  290): wait for playback complete
,I/AudioPlayer(  290): First fillBuffer call!!
I/AudioPlayer(  290): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  290): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  290): postAudioEOS delayUs (0)
V/AwesomePlayer(  290): onCheckAudioStatus
V/AwesomePlayer(  290): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  290): onStreamDone
V/AwesomePlayer(  290): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  290): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 2, 0, 0)
V/AudioCache(  290): playback complete - thread will wake up later
V/AwesomePlayer(  290): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 7, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  290): addBatteryData
V/AudioCache(  290): wait - success
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
D/AudioPlayer(  290): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop() sendCommand(0x7b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  290): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  290): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  290): ~OggSource --
I/OggExtractor(  290): ~OggExtractor ++
I/OggExtractor(  290): ~MyVorbisExtractor ++ 
I/OggExtractor(  290): ~MyVorbisExtractor --
I/OggExtractor(  290): ~OggExtractor --
,I/AudioPlayer(  290): reset out
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  290): SecVideoCapture destructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): mSecCapture clear
I/SecMediaClock(  290): SecMediaClock destructor
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): ~StagefrightPlayer
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/AwesomePlayer(  290): destructor
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/MediaPlayer( 7916): decode(42, 19129712, 4804)
V/MediaPlayerService(  290): decode(30, 19129712, 4804)
,V/MediaPlayerService(  290): player type = 3
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): constructor
,V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): StagefrightPlayer
V/AwesomePlayer(  290): setListener
V/StagefrightPlayer(  290): initCheck
V/AwesomePlayer(  290): setAudioSink
V/StagefrightPlayer(  290): setDataSource(30, 19129712, 4804)
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
D/Utils   (  290): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  290): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  290): mBitrate = -1 bits/sec
,I/OggExtractor(  290): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  290): current audio track index (0) is added to vector
V/AwesomePlayer(  290): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  290): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  290): prepare
V/AwesomePlayer(  290): prepareAsync
V/MediaPlayerService(  290): wait for prepare
,V/AwesomePlayer(  290): onPrepareAsyncEvent
,I/SecMediaClock(  290): SecMediaClock constructor
I/SecMediaClock(  290): reset
I/SecVideoCapture(  290): SecVideoCapture constructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): initAudioDecoder
V/AwesomePlayer(  290): checkOffloadExceptions is true
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
,V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  290): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  290): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  290): finishAsyncPrepare_l
,V/AwesomePlayer(  290): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 200, 973, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 5, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache(  290): notify(0xb03ec290, 1, 0, 0)
V/AudioCache(  290): prepared
V/AudioCache(  290): wait - success
V/MediaPlayerService(  290): start
V/StagefrightPlayer(  290): start
V/AwesomePlayer(  290): play
V/AwesomePlayer(  290): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  290): startAudioPlayer_l, sendErrorNotification (0)
,D/AudioPlayer(  290): start of Playback, useOffload 0
,D/ShortcutReceiver( 8022):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  290): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  290): Audio channels(1)
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  290): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  290): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 6, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): addBatteryData
V/MediaPlayerService(  290): wait for playback complete
I/AudioPlayer(  290): First fillBuffer call!!
I/AudioPlayer(  290): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  290): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
,W/libprocessgroup(  842): failed to open /acct/uid_10112/pid_6945/cgroup.procs: No such file or directory
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  290): postAudioEOS delayUs (0)
V/AwesomePlayer(  290): onCheckAudioStatus
,V/AwesomePlayer(  290): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  290): onStreamDone
V/AwesomePlayer(  290): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  290): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 2, 0, 0)
V/AudioCache(  290): playback complete - thread will wake up later
V/AwesomePlayer(  290): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 7, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  290): addBatteryData
V/AudioCache(  290): wait - success
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
D/AudioPlayer(  290): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop() sendCommand(0x7c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  290): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  290): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  290): ~OggSource --
I/OggExtractor(  290): ~OggExtractor ++
I/OggExtractor(  290): ~MyVorbisExtractor ++ 
I/OggExtractor(  290): ~MyVorbisExtractor --
I/OggExtractor(  290): ~OggExtractor --
,I/AudioPlayer(  290): reset out
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  290): SecVideoCapture destructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): mSecCapture clear
I/SecMediaClock(  290): SecMediaClock destructor
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): ~StagefrightPlayer
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/AwesomePlayer(  290): destructor
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/MediaPlayer( 7916): decode(43, 19099164, 9400)
V/MediaPlayerService(  290): decode(30, 19099164, 9400)
,V/MediaPlayerService(  290): player type = 3
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): constructor
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): StagefrightPlayer
V/AwesomePlayer(  290): setListener
V/StagefrightPlayer(  290): initCheck
V/AwesomePlayer(  290): setAudioSink
V/StagefrightPlayer(  290): setDataSource(30, 19099164, 9400)
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
D/Utils   (  290): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  290): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  290): mBitrate = -1 bits/sec
I/OggExtractor(  290): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  290): current audio track index (0) is added to vector
V/AwesomePlayer(  290): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  290): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  290): prepare
V/AwesomePlayer(  290): prepareAsync
V/MediaPlayerService(  290): wait for prepare
,V/AwesomePlayer(  290): onPrepareAsyncEvent
I/SecMediaClock(  290): SecMediaClock constructor
I/SecMediaClock(  290): reset
I/SecVideoCapture(  290): SecVideoCapture constructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): initAudioDecoder
V/AwesomePlayer(  290): checkOffloadExceptions is true
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  290): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  290): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  290): finishAsyncPrepare_l
V/AwesomePlayer(  290): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 200, 973, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 5, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 1, 0, 0)
V/AudioCache(  290): prepared
V/AudioCache(  290): wait - success
V/MediaPlayerService(  290): start
V/StagefrightPlayer(  290): start
V/MediaPlayer( 7916): decode(49, 19172584, 4112)
,V/AwesomePlayer(  290): play
V/AwesomePlayer(  290): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  290): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  290): start of Playback, useOffload 0
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  290): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  290): Audio channels(1)
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  290): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  290): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 6, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): addBatteryData
I/AudioPlayer(  290): First fillBuffer call!!
,V/MediaPlayerService(  290): decode(37, 19172584, 4112)
I/AudioPlayer(  290): >>> setAudioEffect Read mAudioFormat : 1, event : 4587583, value : 4390976
E/AudioPlayer(  290): >>> setAudioEffect Error mAudioFormat : 1, event : 4587583, value : 4390976
,V/MediaPlayerService(  290): player type = 3
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): constructor
,V/MediaPlayerService(  290): wait for playback complete
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): StagefrightPlayer
V/AwesomePlayer(  290): setListener
V/StagefrightPlayer(  290): initCheck
V/AwesomePlayer(  290): setAudioSink
V/StagefrightPlayer(  290): setDataSource(37, 19172584, 4112)
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
D/Utils   (  290): printFileName fd(38) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  290): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  290): mBitrate = -1 bits/sec
I/OggExtractor(  290): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  290): current audio track index (0) is added to vector
V/AwesomePlayer(  290): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  290): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  290): prepare
V/AwesomePlayer(  290): prepareAsync
,V/MediaPlayerService(  290): wait for prepare
,V/AwesomePlayer(  290): onPrepareAsyncEvent
I/SecMediaClock(  290): SecMediaClock constructor
I/SecMediaClock(  290): reset
I/SecVideoCapture(  290): SecVideoCapture constructor
I/SecVideoCapture(  290): reset
,V/AwesomePlayer(  290): initAudioDecoder
V/AwesomePlayer(  290): checkOffloadExceptions is true
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  290): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  290): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  290): finishAsyncPrepare_l
V/AwesomePlayer(  290): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache(  290): notify(0xb1558150, 200, 973, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 5, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
,V/AudioCache(  290): notify(0xb1558150, 1, 0, 0)
V/AudioCache(  290): prepared
V/AudioCache(  290): wait - success
V/MediaPlayerService(  290): start
V/StagefrightPlayer(  290): start
V/AwesomePlayer(  290): play
,V/AwesomePlayer(  290): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  290): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  290): start of Playback, useOffload 0
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  290): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec(  290): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/AwesomePlayer(  290): postAudioEOS delayUs (0)
,V/AwesomePlayer(  290): onCheckAudioStatus
V/AwesomePlayer(  290): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  290): onStreamDone
V/AwesomePlayer(  290): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  290): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 2, 0, 0)
V/AudioCache(  290): playback complete - thread will wake up later
V/AwesomePlayer(  290): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 7, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  290): addBatteryData
V/AudioCache(  290): wait - success
V/StagefrightPlayer(  290): reset
,I/AudioPlayer(  290): Audio channels(1)
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  290): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer(  290): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
D/AudioPlayer(  290): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop() sendCommand(0x7d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  290): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  290): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  290): ~OggSource --
I/OggExtractor(  290): ~OggExtractor ++
I/OggExtractor(  290): ~MyVorbisExtractor ++ 
I/OggExtractor(  290): ~MyVorbisExtractor --
I/OggExtractor(  290): ~OggExtractor --
I/AudioPlayer(  290): First fillBuffer call!!
I/AudioPlayer(  290): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  290): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  290): postAudioEOS delayUs (0)
V/AwesomePlayer(  290): onCheckAudioStatus
V/AudioCache(  290): notify(0xb1558150, 6, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): addBatteryData
,V/MediaPlayerService(  290): wait for playback complete
V/AwesomePlayer(  290): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  290): onStreamDone
V/AwesomePlayer(  290): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  290): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 2, 0, 0)
V/AudioCache(  290): playback complete - thread will wake up later
V/AwesomePlayer(  290): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 7, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  290): addBatteryData
V/AudioCache(  290): wait - success
V/StagefrightPlayer(  290): reset
,V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
D/AudioPlayer(  290): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop() sendCommand(0x7e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  290): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  290): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  290): ~OggSource --
I/OggExtractor(  290): ~OggExtractor ++
I/OggExtractor(  290): ~MyVorbisExtractor ++ 
I/OggExtractor(  290): ~MyVorbisExtractor --
I/OggExtractor(  290): ~OggExtractor --
,I/AudioPlayer(  290): reset out
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  290): SecVideoCapture destructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): mSecCapture clear
I/SecMediaClock(  290): SecMediaClock destructor
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): ~StagefrightPlayer
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/AwesomePlayer(  290): destructor
I/AudioPlayer(  290): reset out
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  290): SecVideoCapture destructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): mSecCapture clear
I/SecMediaClock(  290): SecMediaClock destructor
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): ~StagefrightPlayer
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/AwesomePlayer(  290): destructor
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/MediaPlayer( 7916): decode(44, 19307764, 52024)
V/MediaPlayerService(  290): decode(30, 19307764, 52024)
,V/MediaPlayerService(  290): player type = 3
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): constructor
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): StagefrightPlayer
V/AwesomePlayer(  290): setListener
V/StagefrightPlayer(  290): initCheck
V/AwesomePlayer(  290): setAudioSink
V/StagefrightPlayer(  290): setDataSource(30, 19307764, 52024)
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
D/Utils   (  290): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  290): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  290): mBitrate = -1 bits/sec
I/OggExtractor(  290): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  290): current audio track index (0) is added to vector
I/ActivityManager(  842): Killing 6960:com.samsung.android.magazine.service/u0a118 (adj 15): bgCount ##41
V/AwesomePlayer(  290): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  290): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  290): prepare
V/AwesomePlayer(  290): prepareAsync
V/MediaPlayerService(  290): wait for prepare
V/AwesomePlayer(  290): onPrepareAsyncEvent
I/SecMediaClock(  290): SecMediaClock constructor
I/SecMediaClock(  290): reset
I/SecVideoCapture(  290): SecVideoCapture constructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): initAudioDecoder
V/AwesomePlayer(  290): checkOffloadExceptions is true
V/AudioPolicyManager(  290): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  290): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  290): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer(  290): finishAsyncPrepare_l
V/AwesomePlayer(  290): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 200, 973, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 5, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 1, 0, 0)
V/AudioCache(  290): prepared
V/AudioCache(  290): wait - success
V/MediaPlayerService(  290): start
V/StagefrightPlayer(  290): start
V/AwesomePlayer(  290): play
V/AwesomePlayer(  290): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  290): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  290): start of Playback, useOffload 0
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  290): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  290): Audio channels(2)
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  290): open(48000, 2, 0x0, 1, 0)
V/AwesomePlayer(  290): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 6, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): addBatteryData
I/AudioPlayer(  290): First fillBuffer call!!
V/MediaPlayerService(  290): wait for playback complete
,D/PackageBroadcastService( 2472): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/PeopleContactsSync( 2472): CP2 sync disabled
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  290): postAudioEOS delayUs (0)
,V/AwesomePlayer(  290): onCheckAudioStatus
V/AwesomePlayer(  290): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  290): onStreamDone
V/AwesomePlayer(  290): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  290): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 2, 0, 0)
V/AudioCache(  290): playback complete - thread will wake up later
V/AwesomePlayer(  290): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 7, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  290): addBatteryData
,V/AudioCache(  290): wait - success
V/StagefrightPlayer(  290): reset
,V/AwesomePlayer(  290): reset_l()
,V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924ba0, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
D/AudioPlayer(  290): reset: mPlaying=0 mReachedEOS=1 useOffload=0
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop() sendCommand(0x7f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  290): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  290): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor(  290): ~OggSource --
I/OggExtractor(  290): ~OggExtractor ++
W/libprocessgroup(  842): failed to open /acct/uid_10118/pid_6960/cgroup.procs: No such file or directory
I/OggExtractor(  290): ~MyVorbisExtractor ++ 
I/OggExtractor(  290): ~MyVorbisExtractor --
I/OggExtractor(  290): ~OggExtractor --
,I/AudioPlayer(  290): reset out
,V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  290): SecVideoCapture destructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): mSecCapture clear
I/SecMediaClock(  290): SecMediaClock destructor
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): ~StagefrightPlayer
,V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
,V/AwesomePlayer(  290): mSecMediaClock clear
V/AwesomePlayer(  290): destructor
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
,V/MediaPlayer( 7916): decode(45, 19172584, 4112)
V/MediaPlayerService(  290): decode(30, 19172584, 4112)
,V/MediaPlayerService(  290): player type = 3
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): constructor
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): StagefrightPlayer
V/AwesomePlayer(  290): setListener
V/StagefrightPlayer(  290): initCheck
V/AwesomePlayer(  290): setAudioSink
V/StagefrightPlayer(  290): setDataSource(30, 19172584, 4112)
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
D/Utils   (  290): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
,V/AwesomePlayer(  290): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  290): mBitrate = -1 bits/sec
I/OggExtractor(  290): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  290): current audio track index (0) is added to vector
V/AwesomePlayer(  290): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  290): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  290): prepare
V/AwesomePlayer(  290): prepareAsync
V/MediaPlayerService(  290): wait for prepare
V/AwesomePlayer(  290): onPrepareAsyncEvent
I/SecMediaClock(  290): SecMediaClock constructor
I/SecMediaClock(  290): reset
I/SecVideoCapture(  290): SecVideoCapture constructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): initAudioDecoder
V/AwesomePlayer(  290): checkOffloadExceptions is true
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  290): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  290): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  290): finishAsyncPrepare_l
V/AwesomePlayer(  290): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 200, 973, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache(  290): notify(0xb15581a0, 5, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 1, 0, 0)
V/AudioCache(  290): prepared
V/AudioCache(  290): wait - success
V/MediaPlayerService(  290): start
V/StagefrightPlayer(  290): start
,V/AwesomePlayer(  290): play
V/AwesomePlayer(  290): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  290): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  290): start of Playback, useOffload 0
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  290): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  290): Audio channels(1)
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache(  290): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer(  290): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
,V/AudioCache(  290): notify(0xb15581a0, 6, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): addBatteryData
V/MediaPlayerService(  290): wait for playback complete
I/AudioPlayer(  290): First fillBuffer call!!
I/AudioPlayer(  290): >>> setAudioEffect Read mAudioFormat : 1, event : 168430090, value : 151652874
E/AudioPlayer(  290): >>> setAudioEffect Error mAudioFormat : 1, event : 168430090, value : 151652874
V/AwesomePlayer(  290): postAudioEOS delayUs (0)
V/AwesomePlayer(  290): onCheckAudioStatus
V/AwesomePlayer(  290): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer(  290): onStreamDone
V/AwesomePlayer(  290): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  290): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 2, 0, 0)
V/AudioCache(  290): playback complete - thread will wake up later
V/AwesomePlayer(  290): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 7, 0, 0)
V/AudioCache(  290): ignored
,V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  290): addBatteryData
V/AudioCache(  290): wait - success
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb15581a0, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  290): mAudioTrackVector clear
D/AudioPlayer(  290): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop() sendCommand(0x80, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  290): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  290): OggSource::~OggSource() mExtractor !mStarted ref count = 1
,I/OggExtractor(  290): ~OggSource --
I/OggExtractor(  290): ~OggExtractor ++
I/OggExtractor(  290): ~MyVorbisExtractor ++ 
I/OggExtractor(  290): ~MyVorbisExtractor --
I/OggExtractor(  290): ~OggExtractor --
I/AudioPlayer(  290): reset out
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  290): SecVideoCapture destructor
I/SecVideoCapture(  290): reset
,V/AwesomePlayer(  290): mSecCapture clear
I/SecMediaClock(  290): SecMediaClock destructor
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): ~StagefrightPlayer
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/AwesomePlayer(  290): destructor
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
,V/AwesomePlayer(  290): mSecMediaClock clear
V/MediaPlayer( 7916): decode(46, 19235660, 21825)
V/MediaPlayerService(  290): decode(30, 19235660, 21825)
V/MediaPlayerService(  290): player type = 3
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): constructor
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): StagefrightPlayer
V/AwesomePlayer(  290): setListener
V/StagefrightPlayer(  290): initCheck
V/AwesomePlayer(  290): setAudioSink
,V/StagefrightPlayer(  290): setDataSource(30, 19235660, 21825)
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
,V/AwesomePlayer(  290): mSecMediaClock clear
D/Utils   (  290): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  290): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  290): mBitrate = -1 bits/sec
I/OggExtractor(  290): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  290): current audio track index (0) is added to vector
V/AwesomePlayer(  290): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  290): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService(  290): prepare
V/AwesomePlayer(  290): prepareAsync
V/MediaPlayerService(  290): wait for prepare
V/AwesomePlayer(  290): onPrepareAsyncEvent
I/SecMediaClock(  290): SecMediaClock constructor
I/SecMediaClock(  290): reset
I/SecVideoCapture(  290): SecVideoCapture constructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): initAudioDecoder
,V/AwesomePlayer(  290): checkOffloadExceptions is true
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  290): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  290): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  290): finishAsyncPrepare_l
V/AwesomePlayer(  290): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 200, 973, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache(  290): notify(0xb03ec290, 5, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 1, 0, 0)
V/AudioCache(  290): prepared
V/AudioCache(  290): wait - success
V/MediaPlayerService(  290): start
V/StagefrightPlayer(  290): start
V/AwesomePlayer(  290): play
,V/AwesomePlayer(  290): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  290): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  290): start of Playback, useOffload 0
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec(  290): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  290): Audio channels(2),
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  290): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  290): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 6, 0, 0)
V/AudioCache(  290): ignored
,V/AwesomePlayer(  290): addBatteryData
V/MediaPlayerService(  290): wait for playback complete
I/AudioPlayer(  290): First fillBuffer call!!
I/AudioPlayer(  290): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  290): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  290): postAudioEOS delayUs (0)
V/AwesomePlayer(  290): onCheckAudioStatus
V/AwesomePlayer(  290): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  290): onStreamDone
V/AwesomePlayer(  290): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  290): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 2, 0, 0)
V/AudioCache(  290): playback complete - thread will wake up later
V/AwesomePlayer(  290): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 7, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer(  290): addBatteryData
V/AudioCache(  290): wait - success
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb03ec290, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
D/AudioPlayer(  290): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop() sendCommand(0x81, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor(  290): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  290): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  290): ~OggSource --
I/OggExtractor(  290): ~OggExtractor ++
I/OggExtractor(  290): ~MyVorbisExtractor ++ 
I/OggExtractor(  290): ~MyVorbisExtractor --
I/OggExtractor(  290): ~OggExtractor --
,I/AudioPlayer(  290): reset out
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  290): SecVideoCapture destructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): mSecCapture clear
I/SecMediaClock(  290): SecMediaClock destructor
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): ~StagefrightPlayer
,V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
,V/AwesomePlayer(  290): destructor
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
,V/MediaPlayer( 7916): decode(47, 19134596, 21552)
V/MediaPlayerService(  290): decode(30, 19134596, 21552)
V/MediaPlayerService(  290): player type = 3
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): constructor
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): StagefrightPlayer
V/AwesomePlayer(  290): setListener
V/StagefrightPlayer(  290): initCheck
V/AwesomePlayer(  290): setAudioSink
V/StagefrightPlayer(  290): setDataSource(30, 19134596, 21552)
,V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
,V/AwesomePlayer(  290): mSecMediaClock clear
D/Utils   (  290): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  290): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  290): mBitrate = -1 bits/sec
I/OggExtractor(  290): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  290): current audio track index (0) is added to vector
V/AwesomePlayer(  290): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  290): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService(  290): prepare
V/AwesomePlayer(  290): prepareAsync
V/MediaPlayerService(  290): wait for prepare
V/AwesomePlayer(  290): onPrepareAsyncEvent
I/SecMediaClock(  290): SecMediaClock constructor
I/SecMediaClock(  290): reset
I/SecVideoCapture(  290): SecVideoCapture constructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): initAudioDecoder
,V/AwesomePlayer(  290): checkOffloadExceptions is true
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  290): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  290): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  290): finishAsyncPrepare_l
V/AwesomePlayer(  290): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 200, 973, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
,V/AudioCache(  290): notify(0xb1558150, 5, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 1, 0, 0)
V/AudioCache(  290): prepared
V/AudioCache(  290): wait - success
V/MediaPlayerService(  290): start
V/StagefrightPlayer(  290): start
,V/AwesomePlayer(  290): play
V/AwesomePlayer(  290): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer(  290): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  290): start of Playback, useOffload 0
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer(  290): Audio channels(2)
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  290): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer(  290): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 6, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): addBatteryData
V/MediaPlayerService(  290): wait for playback complete
I/AudioPlayer(  290): First fillBuffer call!!
I/AudioPlayer(  290): >>> setAudioEffect Read mAudioFormat : 1, event : 4292761, value : -2137358184
E/AudioPlayer(  290): >>> setAudioEffect Error mAudioFormat : 1, event : 4292761, value : -2137358184
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  290): postAudioEOS delayUs (0)
,V/AwesomePlayer(  290): onCheckAudioStatus
V/AwesomePlayer(  290): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  290): onStreamDone
V/AwesomePlayer(  290): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  290): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb1558150, 2, 0, 0)
V/AudioCache(  290): playback complete - thread will wake up later
V/AwesomePlayer(  290): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  290): notify(0xb1558150, 7, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  290): addBatteryData
V/AudioCache(  290): wait - success
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AudioCache(  290): notify(0xb1558150, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
D/AudioPlayer(  290): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop() sendCommand(0x82, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  290): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  290): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  290): ~OggSource --
I/OggExtractor(  290): ~OggExtractor ++
I/OggExtractor(  290): ~MyVorbisExtractor ++ 
I/OggExtractor(  290): ~MyVorbisExtractor --
I/OggExtractor(  290): ~OggExtractor --
,I/AudioPlayer(  290): reset out
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture(  290): SecVideoCapture destructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): mSecCapture clear
I/SecMediaClock(  290): SecMediaClock destructor
V/AwesomePlayer(  290): mSecMediaClock clear
,V/StagefrightPlayer(  290): ~StagefrightPlayer
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
,V/AwesomePlayer(  290): mSecMediaClock clear
V/AwesomePlayer(  290): destructor
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
,V/AwesomePlayer(  290): mSecMediaClock clear
V/MediaPlayer( 7916): decode(48, 19228560, 7017)
V/MediaPlayerService(  290): decode(30, 19228560, 7017)
V/MediaPlayerService(  290): player type = 3
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): constructor
V/AwesomePlayer(  290): setDefault
V/AwesomePlayer(  290): reset_l()
,V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): StagefrightPlayer
V/AwesomePlayer(  290): setListener
V/StagefrightPlayer(  290): initCheck
V/AwesomePlayer(  290): setAudioSink
,V/StagefrightPlayer(  290): setDataSource(30, 19228560, 7017)
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 8, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
,V/AwesomePlayer(  290): mSecMediaClock clear
D/Utils   (  290): printFileName fd(31) -> /system/priv-app/SHealth3_5/SHealth3_5.apk
V/AwesomePlayer(  290): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  290): mBitrate = -1 bits/sec
I/OggExtractor(  290): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer(  290): current audio track index (0) is added to vector
V/AwesomePlayer(  290): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer(  290): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService(  290): prepare
,V/AwesomePlayer(  290): prepareAsync
V/MediaPlayerService(  290): wait for prepare
V/AwesomePlayer(  290): onPrepareAsyncEvent
I/SecMediaClock(  290): SecMediaClock constructor
I/SecMediaClock(  290): reset
I/SecVideoCapture(  290): SecVideoCapture constructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): initAudioDecoder
V/AwesomePlayer(  290): checkOffloadExceptions is true
,V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec(  290): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  290): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/AwesomePlayer(  290): Could not offload audio decode, try pcm offload
V/AudioPolicyManager(  290): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager(  290): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer(  290): finishAsyncPrepare_l
V/AwesomePlayer(  290): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 200, 973, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 5, 0, 0)
,V/AudioCache(  290): ignored
V/AwesomePlayer(  290): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 1, 0, 0)
V/AudioCache(  290): prepared
V/AudioCache(  290): wait - success
V/MediaPlayerService(  290): start
V/StagefrightPlayer(  290): start
V/AwesomePlayer(  290): play
V/AwesomePlayer(  290): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer(  290): startAudioPlayer_l, sendErrorNotification (0)
D/AudioPlayer(  290): start of Playback, useOffload 0
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7,
I/OMXCodec(  290): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec(  290): >>>UHQA initOutputFormat 16
I/OMXCodec(  290): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer(  290): Audio channels(2)
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat:0, 1, 0
I/AudioPlayer(  290): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache(  290): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer(  290): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 6, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): addBatteryData
,V/MediaPlayerService(  290): wait for playback complete
I/AudioPlayer(  290): First fillBuffer call!!
I/AudioPlayer(  290): >>> setAudioEffect Read mAudioFormat : 1, event : 235670794, value : 319688206
E/AudioPlayer(  290): >>> setAudioEffect Error mAudioFormat : 1, event : 235670794, value : 319688206
I/SecureStorage(  360): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  360): [INFO]: SPID(0x00000005)PID: 7938, TID: 7949
,I/OMXCodec(  290): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer(  290): postAudioEOS delayUs (0)
V/AwesomePlayer(  290): onCheckAudioStatus
,V/AwesomePlayer(  290): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer(  290): onStreamDone
V/AwesomePlayer(  290): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer(  290): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 2, 0, 0)
V/AudioCache(  290): playback complete - thread will wake up later
V/AwesomePlayer(  290): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache(  290): notify(0xb0924c90, 7, 0, 0)
V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer(  290): addBatteryData
V/AudioCache(  290): wait - success
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache(  290): notify(0xb0924c90, 8, 0, 0)
,V/AudioCache(  290): ignored
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
D/AudioPlayer(  290): reset: mPlaying=0 mReachedEOS=1 useOffload=0
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stop() sendCommand(0x83, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec(  290): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec(  290): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
,I/OggExtractor(  290): OggSource::stop() mExtractor ref count = 1
I/OggExtractor(  290): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor(  290): ~OggSource --
I/OggExtractor(  290): ~OggExtractor ++
I/OggExtractor(  290): ~MyVorbisExtractor ++ 
I/OggExtractor(  290): ~MyVorbisExtractor --
I/OggExtractor(  290): ~OggExtractor --
I/AudioPlayer(  290): reset out
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
,I/SecVideoCapture(  290): SecVideoCapture destructor
I/SecVideoCapture(  290): reset
V/AwesomePlayer(  290): mSecCapture clear
I/SecMediaClock(  290): SecMediaClock destructor
V/AwesomePlayer(  290): mSecMediaClock clear
V/StagefrightPlayer(  290): ~StagefrightPlayer
V/StagefrightPlayer(  290): reset
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
,V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
V/AwesomePlayer(  290): destructor
V/AwesomePlayer(  290): reset_l()
V/AwesomePlayer(  290): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer(  290): cancelPlayerEvents (keepNotifications=0)
,V/AwesomePlayer(  290): mAudioTrackVector clear
V/AwesomePlayer(  290): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer(  290): mSecCapture clear
V/AwesomePlayer(  290): mSecMediaClock clear
,I/SecureStorage( 7938): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 7938): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,I/SecSQLiteOpenHelper( 7916): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper( 7916): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper( 7916): Open platform.db in secure mode
,D/SecSQLiteDatabase( 7916): Android Version: 5.0
D/SecSQLiteDatabase( 7916): Load library secsqlite.so for Android 5.0
,I/SecSQLiteDatabase( 7916): openSecureDatabase...
,I/SecSQLiteDatabase( 7916): private openSecureDatabase...
I/SecSQLiteConnectionPool( 7916): OpenSecure
I/SecSQLiteConnectionPool( 7916): OpenSecure with password
I/SecSQLiteConnectionPool( 7916): openSecureConnectionLocked
,I/SecSQLiteDatabase( 7916): ...private openSecureDatabase
I/SecSQLiteDatabase( 7916): ...openSecureDatabase
,I/SecSQLiteOpenHelper( 7916): ...getDatabaseLocked(b,b,pwd)
,D/SecSQLiteOpenHelper( 7916): ...getDatabaseLocked(b,b,pwd)
,W/System.err( 7916): java.lang.NumberFormatException: Invalid int: "null"
,W/System.err( 7916): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err( 7916): 	at java.lang.Integer.parseInt(Integer.java:358)
,W/System.err( 7916): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 7916): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:449)
W/System.err( 7916): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1173)
W/System.err( 7916): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7916): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7916): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 7916): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/SMD     (  285): DCD ON
,I/ActivityManager(  842): Waited long enough for: ServiceRecord{8d26bee u0 com.samsung.dcm/.framework.FrameworkService}
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/GAV3    ( 7916): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  285): DCD ON
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/FactoryTest( 6407): Not factory mode
,D/FactoryTest( 6407): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6407): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6407): still no open session command from host, so toast
,W/ContextImpl( 6407): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6407): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6407): Timeline: Activity_launch_request id:com.android.settings time:113998
,E/PersonaManagerService(  842): inState():  stateMachine is null !!
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  842): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  842): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/MTPRx   ( 6407): started activity for popup
,I/SQLiteSecureOpenHelper( 3579): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3579): getDatabaseLocked(b,b,pwd)...
,D/ResourcesManager( 6407): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/ResourcesManager( 6407): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6407): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6407): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6407): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6407): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6407): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6407): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/SSRM:m  (  842): SIOP:: AP = 360, PST = 419, CUR = 300
,E/SettingsReceiverActivity( 6407): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/InputMethodManagerService(  842): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  842): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@33abedec attribute=null, token = android.os.BinderProxy@ee88494
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6407): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6407): dev.kiessupport is : TRUE
,D/Activity( 6407): performCreate Call secproduct feature valuefalse
,D/Activity( 6407): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ActivityManager(  842): post active user change for 0
,D/KnoxTimeoutHandler(  842): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  842): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/Timeline( 7269): Timeline: Activity_idle id: android.os.BinderProxy@f710488 time:114323
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :4
,D/BatteryService(  842): level:100, scale:100, status:2, health:2, present:true, voltage: 4386, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): stay LED for charging
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6579): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6579): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6579): [1] 5.onFinished: Scheduling replication attempt 3.
,I/art     (  842): Explicit concurrent mark sweep GC freed 60019(3MB) AllocSpace objects, 14(419KB) LOS objects, 30% free, 36MB/52MB, paused 1.986ms total 223.576ms
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ActivityManager(  842): mDVFSHelper.release()
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :4
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/PowerManagerService(  842): [PWL] Off : 50s ago
,D/SSRM:m  (  842): SIOP:: AP = 340, PST = 406, CUR = 300
,D/X       (  842): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ContentApp( 1226):  LEVEL : -1
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,I/SystemBroadcastReceiver( 7074): [#DCM#] [DCM_Performance] onReceive completed in time  404 microsec. 
,E/Zygote  ( 8155): MountEmulatedStorage()
,E/Zygote  ( 8155): v2
,I/libpersona( 8155): KNOX_SDCARD checking this for 10054
I/libpersona( 8155): KNOX_SDCARD not a persona
,I/ActivityManager(  842): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=8155 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/SystemBroadcastReceiver( 7074): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7074): [#DCM#] onReceive action = EVENT_SIOP
,I/SELinux ( 8155): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8155): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8155): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8155): TimaSignature is unavailable
,D/ActivityThread( 8155): Added TimaKeyStore provider
,D/ResourcesManager( 8155): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8155): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8155): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8155): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 8155): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8155): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/SMD     (  285): DCD ON
,E/TranscodeReceiver( 8155): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 8155): core_num = 4
,W/linker  ( 8155): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 8155): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 8155): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
,D/videowall-Global( 8155): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 8155):  SIOP_LEVEL: -1
,I/ActivityManager(  842): Killing 6978:com.samsung.helphub/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_6978/cgroup.procs: No such file or directory
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/LightsService(  842): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 842) 
,D/LightsService(  842): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x12 -> 0x42 | SvcLED(id=3) set On
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
,D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,E/LightSensor(  842): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/SensorManager(  842): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  842): turn on LED for fully charged
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -2
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId -2 pkgname com.android.systemui
,D/WindowManager(  842): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService(  842): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1171
,I/PowerManagerService(  842): !@[ps] Screen__On wl: PowerUI.Notification
I/PowerManagerService(  842): Waking up from sleep (uid 10059)...
,V/KeyguardServiceDelegate(  842): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@31a7afe0)
,D/KeyguardViewMediator( 1171): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1171): notifyScreenOnLocked
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/PowerManagerService(  842): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  842): [s] UserActivityState : 0 -> 1
,I/DisplayPowerController(  842): Blocking screen on until initial contents have been drawn.
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/SContextService(  842): 	.registerCallback : 1, client=
,D/AutomaticBrightnessController(  842): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/DisplayPowerController(  842): getFinalBrightness : 0 -> 0
,D/AutomaticBrightnessController(  842): [DAB] setLightSensorEnabled : registerListener mLightSensor
,D/PowerManagerService(  842): [PWL] sb acquire: PowerManagerService.Display
,D/AutomaticBrightnessController(  842): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
I/AutomaticBrightnessController(  842): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 1
,I/AutomaticBrightnessController(  842): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/PowerManagerService(  842): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
,D/MISC PowerHAL(  842): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL(  842): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
W/CAE     (  842): setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/QCOM PowerHAL(  842): Got set_interactive hint
,I/DisplayManagerService(  842): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SensorManager(  842): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/PowerManagerService(  842): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 27ms
D/SurfaceFlinger(  249): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Unblanking display: 0
,E/Sensors (  842): Acc old sensor_state 8704, new sensor_state : 8705 en : 1
I/CAE     (  842): setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
,I/CAE     (  842): setCAProperty(ContextAwareService.java:469) - result : true
,W/CAE     (  842): setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  842): sendProperty() : service = Auto Rotation
,D/SensorManager(  842): registerListener :: 0, MPU6500 Acceleration Sensor, 200000, 0,  
D/PowerManagerService(  842): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 9ms
W/CAE     (  842): registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  842): start(ContextProvider.java:126)
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,V/CAE     (  842): clear(AutoRotationRunner.java:182)
,V/BitmapFactory( 1171): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_battery_full.png
,V/CAE     (  842): enable(AutoRotationRunner.java:158)
,I/CAE     (  842): sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
,D/SensorHubManager(  842): SendSensorHubData: send data = -79, 7, 0, 0
,D/Sensorhubs(  297): sendContextData: -79, 7, 0, 0
,D/CAE     (  842): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  842): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,V/BitmapFactory( 1171): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_battery_full.png
,D/KnoxNotification( 1171): ----- inflateViews : modified publicViewLocal -----
,D/CAE     (  842): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  842): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,D/CAE     (  842): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
I/CAE     (  842): showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@200ab3fa, Service : AUTO_ROTATION(1)
,W/CAE     (  842): registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  842): addSContextService() : service = Auto Rotation
D/SContextService(  842): ===== SContext Service List =====
,D/SContextService(  842): Listener : android.hardware.scontext.SContextService$Listener@14c0fdab, Service : Auto Rotation
D/SContextManager(  842):   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@233c5299, service=Auto Rotation
D/KnoxNotification( 1171): ----- inflateViews : modified KnoxViewLocal -----
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PersonaManager( 1171): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1171): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@322b94a4
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
,D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
D/InputManager-JNI(  842): setDeviceInteractive: 1
,D/InputManager-JNI(  842): sysfs_write +: /sys/class/input/event1/device/enabled: 1
,D/InputManager-JNI(  842): sysfs_write +: /sys/class/input/event2/device/enabled: 1
,D/KeyguardViewMediator( 1171): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1171): onScreenTurnedOn()
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1171): value : false
,D/SamsungIME( 1831): showDlgMsgBox : false true true
,D/ActivityManager(  842): post active user change for 0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/KnoxTimeoutHandler(  842): postActiveUserChange for user 0
,D/NfcService( 1454): call the applyRotuiing
,D/StatusBarKeyguardViewManager( 1171): callback.onShown()
V/KeyguardServiceDelegate(  842): **** SHOWN CALLED ****
D/DisplayPowerController(  842): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
V/UserPresentBroadcastReceiver( 2197): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/DisplayPowerController(  842): Unblocked screen on after 186 ms
D/DisplayPowerState(  842): !@ ColorFade exit
,I/SurfaceFlinger(  249): id=13 Removed ColorFade (8/8)
,I/SurfaceFlinger(  249): id=13 Removed ColorFade (-2/8)
E/libEGL  (  842): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/Adreno-ES20( 7269): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 7269): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/StatusBar.NetworkController( 1171): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/BatteryMeterView( 1171): onDraw batteryColor : -1
,I/rmt_storage(  271): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
I/rmt_storage(  271): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  271): wakelock acquired: 1, error no: 42
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228406656)
,D/InputManager-JNI(  842): sysfs_write -: /sys/class/input/event2/device/enabled: 1
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 1
,I/Timeline( 7269): Timeline: Activity_idle id: android.os.BinderProxy@f710488 time:126191
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228406656) wakelock released: 1, error no: 22
I/rmt_storage(  271): 
,E/qdexternal(  249): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  249): hwc_blank: Done unblanking display: 0
,D/SurfaceControl(  842): Excessive delay in setPowerMode(): 287ms
,I/rmt_storage(  271): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
,D/lights  (  842): lcd : 8 +
,D/lights  (  842): lcd : 8 -
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
D/PowerManagerService(  842): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  842): SecHardwareInterface.setBatteryADC : true
,D/PowerManagerService(  842): [input device light] setInputDeviceLightOn is called : 1
,D/PowerManagerService(  842): [input device light] handleInputDeviceLightOn
D/lights  (  842): button : 1 +
D/lights  (  842): button : 1 -
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  842): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  842): unregisterListener ::   
D/LightsService(  842): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,D/InputManager-JNI(  842): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,V/ActivityManager(  842): Display changed displayId=0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/ResourcesManager(  842): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PalmMotion(  842): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotion(  842): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,D/LightsService(  842): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 842) 
D/LightsService(  842): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x42 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService(  842): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  842): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  842): unregisterListener ::   
D/lights  (  842): led_pattern : 5 +
,D/SSRM:a  (  842): DeviceInfo:: 000000000000
,D/SSRM:a  (  842): SettingsAirViewInfo:: 000000000
D/KnoxTimeoutHandler(  842): handleActiveUserChange for user 0
,D/LightsService(  842): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 842) 
,D/SLocation(  842): handleMessage got exceptionjava.lang.NullPointerException: Attempt to invoke virtual method 'void com.samsung.location.currentloc.SCurrentLocationManager.handleSCurLocScreenOn()' on a null object reference
D/lights  (  842): led_pattern : 5 -
D/LightsService(  842): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=4) OUT; SvcLED(id=3) IN
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'void com.samsung.location.currentloc.SCurrentLocationManager.handleSCurLocScreenOn()' on a null object reference
,D/LightsService(  842): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService(  842): turn off LED
,D/LightsService(  842): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/lights  (  842): led_pattern : 0 +
,W/System.err(  842): 	at com.samsung.location.lib.h.handleMessage(Unknown Source)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at com.samsung.location.SLocationService.run(Unknown Source)
W/System.err(  842): 	at java.lang.Thread.run(Thread.java:818)
,I/CAE     (  842): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     (  842): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
D/lights  (  842): led_pattern : 0 -
D/LightsService(  842): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     (  842): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager(  842): SendSensorHubData: send data = -76, 13, -47, 0
,D/Sensorhubs(  297): sendContextData: -76, 13, -47, 0
,D/InputMethodManagerService(  842): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService(  842):  handler : SCREEN_ON end
,D/NotificationService(  842): ACTION_SCREEN_ON
,D/LightsService(  842): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 842) 
D/LightsService(  842): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  842): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  842): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/WifiStateMachine(  842): backgroundScan enabled=false startBackgroundScanIfNeeded:false
,E/WifiStateMachine(  842): handleScreenStateChanged Exit: true
,D/audio_hw_primary(  290): adev_set_parameters: enter: screen_state=on
,V/voice   (  290): voice_set_parameters: enter: screen_state=on
V/voice   (  290): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  290): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  290): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  290): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  290): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  842): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/IpRemoteDisplayController(  842): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  842): Bridge Server is not available
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,E/WifiStateMachine(  842): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  842): do suspend false
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/PersonaManagerService(  842): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler(  842): MSG_ACTION_SCREEN_ON called
,I/wpa_supplicant( 1293): reset timer : RESET_TIMER 1
I/wpa_supplicant( 1293): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1293): P2P: Current p2p state = IDLE
,I/NfcService( 1454): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,I/wpa_supplicant( 1293): Scan requested (ret=0) - scan timeout 30 seconds
,D/NfcService( 1454): call the applyRotuiing
,D/accuweather( 2058): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 2058): [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
D/accuweather( 2058): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/accuweather( 2058): [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
,D/accuweather( 2058): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/accuweather( 2058): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
,D/SurfaceWidget.Renderer( 2058): [237392/6] SurfaceWidget drawing first frame
,I/SamsungIME( 1831): getNextShiftState() cursorCapsMode : 0
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SurfaceWidget.Renderer( 2058): [237392/6] SurfaceWidget drawing first frame
,I/SystemBroadcastReceiver( 7074): [#DCM#] [DCM_Performance] onReceive completed in time  198 microsec. 
,D/PowerManagerService(  842): [PWL] sb release: PowerManagerService.Broadcasts
,I/SystemBroadcastReceiver( 7074): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7074): [#DCM#] onReceive action = EVENT_SCREEN_ON
I/DCMController( 7074): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_ON
,I/DatabaseRebuilderTask( 7074): [#DCM#] createLuceneReader done 
I/DatabaseRebuilderTask( 7074): [#DCM#] resyncLocation   
I/DatabaseRebuilderTask( 7074): [#DCM#] resyncLocation: querying only for documents with deleted = 0 
,I/DatabaseRebuilderTask( 7074): [#DCM#] topDocs hits = 0
I/DatabaseRebuilderTask( 7074): [#DCM#] No of Location data to be added:  0
I/DatabaseRebuilderTask( 7074): [#DCM#] releaseLuceneReader done 
,I/DatabaseRebuilderTask( 7074): [#DCM#] Starting media manager do operation 
,I/SystemUtils( 7074): [#DCM#] setHeavySharedPref set as  false
,D/SSRM:m  (  842): SIOP:: AP = 340, PST = 392, CUR = 300
,I/IntentHandler( 7074): [#DCM#] Stopping service with ids up to  1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,I/DCMThreadPoolExecutor( 7074): [#DCM#] afterExecute FutureTask
I/DCMController( 7074): [#DCM#] task finished =  com.samsung.dcm.framework.extractormanager.task.DatabaseRebuilderTask@19b12915
,I/ActivityManager(  842): Killing 7012:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,D/daemonapp( 1380): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1380): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
,D/daemonapp( 1380): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1380): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1380): [MSC_Daemon]>>> WDSM:41 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1380): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1380): [MSC_Daemon]>>> daemonapp [Version : 15010801 ] [ 2 ] 
,D/comsamsunglog( 1380): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1380): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1380): [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,D/daemonapp( 1380): [MSC_Daemon]>>> WDSM:418 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1380): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1380): [MSC_Daemon]>>> WDSM:421 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1380): [MSC_Daemon]>>> WDSM:422 [0:0] [ASO][NUT] = 1454455500000
D/daemonapp( 1380): [MSC_Daemon]>>> WDSM:423 [0:0] [ASO][CT] = 1454434003294
,D/daemonapp( 1380): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/SQLiteLog( 1638): (10) POSIX Error : 11 SQLite Error : 3850
,D/daemonapp( 1380): [MSC_Daemon]>>> WU:1622 [0:0] PakNme size = 5
,D/daemonapp( 1380): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1380): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1380): [MSC_Daemon]>>> WU:1626 [0:0] CP Name cp_eng
,D/daemonapp( 1380): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1380): [MSC_Daemon]>>> WU:1606 [0:0] [NameNotFoundException] !!
,W/libprocessgroup(  842): failed to open /acct/uid_10166/pid_7012/cgroup.procs: No such file or directory
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/SSRM:a  (  842): DeviceInfo:: 000000000000
D/SSRM:a  (  842): SettingsAirViewInfo:: 000000000
,E/SMD     (  285): DCD ON
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PowerManagerService(  842): [input device light] handleInputDeviceLightOff
D/lights  (  842): button : 0 +
,D/lights  (  842): button : 0 -
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  842): CMD_RSSI_POLL : calculateWifiScore in!
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
E/WifiStateMachine(  842): calculateWifiScore() report new score 60
I/WifiStateMachine(  842): calculateWifiScore : sendNetworkScore in!
D/ConnectivityService(  842): updateNetworkScore for NetworkAgentInfo [WIFI () - 503] to 60
D/ConnectivityService(  842): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  842):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  842):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  842): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  842): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  842): calling update connectivity
D/ConnectivityService(  842):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/WifiStateMachine(  842): calculateWifiScore : sendNetworkScore out!
D/ConnectivityService(  842):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  842): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524290
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  842): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  842): CMD_RSSI_POLL : out!
,D/ConnectivityService(  842): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560,
D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness(),
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8,
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,I/wpa_supplicant( 1293): nl80211: Received scan results (4 BSSes)
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,D/WifiP2pService(  842): InactiveState{ what=147461 }
,D/WifiP2pService(  842): P2pEnabledState{ what=147461 }
D/WifiP2pService(  842): DefaultState{ what=147461 }
,E/WifiStateMachine(  842): [1,454,434,006,880 ms] noteScanEnd no scan source
,E/WifiStateMachine(  842): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@12d83eda sup_state=COMPLETED debouncing=false
,I/CLocInfoService(  842): External Intent Received android.net.wifi.SCAN_RESULTS
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/WifiStateMachine(  842): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  842): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  842): CMD_RSSI_POLL : out!
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false),
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen,
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/Watchdog(  842): !@Sync 4
,E/SMD     (  285): DCD ON
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  842): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  842): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  842): CMD_RSSI_POLL : out!
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560,
D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,V/AlarmManager(  842): waitForAlarm result :4
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
I/MotionRecognitionService(  842): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 330, PST = 377, CUR = 300
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6579): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6579): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6579): [1] 5.onFinished: Scheduling replication attempt 4.
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  842): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  842): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  842): CMD_RSSI_POLL : out!
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  842): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  842): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  842): CMD_RSSI_POLL : out!
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 3
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,V/AlarmManager(  842): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  842): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  842): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  842): CMD_RSSI_POLL : out!
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  842): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1171 (0x0)
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  842): Plugged
I/MotionRecognitionService(  842): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  842): SIOP:: AP = 320, PST = 366, CUR = 300
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  842): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  842): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  842): CMD_RSSI_POLL : out!
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  842): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  842): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  842): lcd : 1 +
D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,D/lights  (  842): lcd : 1 -
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  842): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  842): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  842): CMD_RSSI_POLL : out!
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/SMD     (  285): DCD ON
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  842): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  842): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  842): CMD_RSSI_POLL : out!
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/SMD     (  285): DCD ON
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness(),
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
,D/DisplayPowerController(  842): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  842): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  842): Nap time (uid 1000)...
I/PowerManagerService(  842): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  842): Going to sleep due to screen timeout (uid 1000)...
,D/PowerManagerService(  842): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  842): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI(  842): setDeviceInteractive: 0
,D/PowerManagerService(  842): handleSandman : startDream()
,D/InputManager-JNI(  842): sysfs_write +: /sys/class/input/event1/device/enabled: 0
E/PowerManagerService(  842): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  842): Sleeping (uid 1000)...
D/PowerManagerService(  842): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  842): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService(  842): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger(  249): id=16 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  842): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  842): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/InputManager-JNI(  842): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService(  842): 	.unregisterCallback : 1, client=
D/SContextService(  842): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@14c0fdab, Service = Auto Rotation, used = 1
,W/CAE     (  842): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  842): stop(ContextProvider.java:149)
,V/CAE     (  842): clear(AutoRotationRunner.java:182)
,V/CAE     (  842): disable(AutoRotationRunner.java:171)
I/CAE     (  842): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
,D/SensorHubManager(  842): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  297): sendContextData: -78, 7, 0, 0
,D/CAE     (  842): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     (  842): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     (  842): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  842): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     (  842): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  842): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  842): removeSContextService() : service = Auto Rotation
D/SContextService(  842): ===== SContext Service List =====
D/SContextManager(  842):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@233c5299, service=Auto Rotation
,D/KeyguardViewMediator( 1171): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1171): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1171): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1171): notifyScreenOffLocked
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/KeyguardViewMediator( 1171): timeout : 5000
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/DisplayPowerController(  842): ColorFade: onAnimationStart
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 0
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 0
,D/lights  (  842): lcd : 0 +
,D/DisplayPowerController(  842): getFinalBrightness : 8 -> 0
,D/lights  (  842): lcd : 0 -
,I/SQLiteSecureOpenHelper( 3579): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3579): getDatabaseLocked(b,b,pwd)...
,D/KeyguardViewMediator( 1171): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1171): handleNotifyScreenOff
,D/LightsService(  842): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 842) 
D/LightsService(  842): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  842): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  842): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  842): unregisterListener ::   
D/lights  (  842): led_pattern : 5 +
,D/BatteryService(  842): turn on LED for fully charged
,D/lights  (  842): led_pattern : 5 -
D/LightsService(  842): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
D/StatusBar.NetworkController( 1171): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): applyOpen
,I/CAE     (  842): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  842): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  842): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  842): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  297): sendContextData: -76, 13, -46, 0
,I/CAE     (  842): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 17, 27, 12,
D/SensorHubManager(  842): SendSensorHubData: send data = -63, 14, 17, 27, 12
D/Sensorhubs(  297): sendContextData: -63, 14, 17, 27, 12
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_SCREEN_OFF
E/MotionRecognitionService(  842):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  842): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  842): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  842): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  842): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  842): do suspend true
,D/NotificationService(  842): ACTION_SCREEN_OFF
D/LightsService(  842): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 842) 
D/LightsService(  842): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService(  842): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  842): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  842): unregisterListener ::   
D/LightsService(  842): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  290): adev_set_parameters: enter: screen_state=off
V/voice   (  290): voice_set_parameters: enter: screen_state=off
V/voice   (  290): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  290): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  290): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  290): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  290): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  842): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  842): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController(  842): Bridge Server is not available
,D/VolumePanel( 1171): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1171): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1171): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1171): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  842): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  842): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1454): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1171):      ACTION_SCREEN_OFF is finished!!!! 
,E/LightSensor(  842): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  842): mCallbacks.updateBrightness()
D/DisplayPowerController(  842): getFinalBrightness : 8 -> 0
,E/StatusBar( 1171): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1171): dismissHelpPopup 
,D/accuweather( 2058): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2058): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2058): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/DisplayPowerState(  842): !@ ColorFade entry
,D/DisplayPowerController(  842): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  842): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/AutomaticBrightnessController(  842): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/AutomaticBrightnessController(  842): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/AutomaticBrightnessController(  842): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,E/LightSensor(  842): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,D/SensorManager(  842): unregisterListener ::   
,E/Sensors (  842): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  842): unregisterListener ::   
,D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,W/ActivityManager(  842): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  842): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,I/SystemBroadcastReceiver( 7074): [#DCM#] [DCM_Performance] onReceive completed in time  384 microsec. 
,D/PowerManagerService(  842): [PWL] sb release: PowerManagerService.Broadcasts
,I/SystemBroadcastReceiver( 7074): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7074): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 7074): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/DisplayPowerController(  842): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  842): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  842): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
V/ActivityManager(  842): Display changed displayId=0
,D/SSRM:m  (  842): SIOP:: AP = 320, PST = 358, CUR = 300
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/StatusBar.NetworkController( 1171): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  842): Excessive delay in setPowerMode(): 258ms
,D/PowerManagerService(  842): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  842): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  842): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  842): Got set_interactive hint
,I/PowerManagerService(  842): [PWL] Off : 0s ago
,I/PowerManagerService(  842): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  842): [PWL]     mDisplayReady : false
D/DisplayPowerController(  842): getFinalBrightness : 0 -> 0
,D/PowerManagerService(  842): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  842): [PWL] sb release: PowerManagerService.Display
,V/AlarmManager(  842): waitForAlarm result :4
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6579): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6579): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6579): [1] 5.onFinished: Scheduling replication attempt 5.
,V/AlarmManager(  842): waitForAlarm result :4
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
D/SecContentProvider2(  842): mCursor = null
,D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/SMD     (  285): DCD ON
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/HttpOperation( 6549): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6549): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6549): 	at kfv.a(PG:65)
E/HttpOperation( 6549): 	at kff.u(PG:385)
E/HttpOperation( 6549): 	at kfb.a(PG:29)
E/HttpOperation( 6549): 	at kff.l(PG:132)
E/HttpOperation( 6549): 	at dsf.a(PG:807)
E/HttpOperation( 6549): 	at fhk.a(PG:1126)
E/HttpOperation( 6549): 	at fhk.a(PG:908)
E/HttpOperation( 6549): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6549): 	at ihi.a(PG:22)
E/HttpOperation( 6549): 	at kft.a(PG:91)
E/HttpOperation( 6549): 	at kfv.a(PG:62)
E/HttpOperation( 6549): 	... 8 more
E/HttpOperation( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6549): 	at gde.c(Unknown Source)
E/HttpOperation( 6549): 	at gde.b(Unknown Source)
E/HttpOperation( 6549): 	at ihi.a(PG:19)
E/HttpOperation( 6549): 	... 10 more
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1638): Explicit concurrent mark sweep GC freed 36156(2MB) AllocSpace objects, 21(1701KB) LOS objects, 40% free, 17MB/29MB, paused 671us total 49.127ms
,D/ResourcesManager( 1638): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6549): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6549): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6549): 	at kfv.a(PG:65)
E/HttpOperation( 6549): 	at kff.u(PG:385)
E/HttpOperation( 6549): 	at kfb.a(PG:29)
E/HttpOperation( 6549): 	at kff.l(PG:132)
E/HttpOperation( 6549): 	at ieo.a(PG:43)
E/HttpOperation( 6549): 	at iep.a(PG:93)
E/HttpOperation( 6549): 	at fhn.a(PG:59)
E/HttpOperation( 6549): 	at lex.a(PG:85)
E/HttpOperation( 6549): 	at lex.b(PG:132)
E/HttpOperation( 6549): 	at fhk.a(PG:1146)
E/HttpOperation( 6549): 	at fhk.a(PG:908)
E/HttpOperation( 6549): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6549): 	at ihi.a(PG:22)
E/HttpOperation( 6549): 	at kft.a(PG:91)
E/HttpOperation( 6549): 	at kfv.a(PG:62)
E/HttpOperation( 6549): 	... 12 more
E/HttpOperation( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6549): 	at gde.c(Unknown Source)
E/HttpOperation( 6549): 	at gde.b(Unknown Source)
E/HttpOperation( 6549): 	at ihi.a(PG:19)
E/HttpOperation( 6549): 	... 14 more
,E/ExperimentLoader( 6549): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6549): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6549): 	at kfv.a(PG:65)
E/ExperimentLoader( 6549): 	at kff.u(PG:385)
E/ExperimentLoader( 6549): 	at kfb.a(PG:29)
E/ExperimentLoader( 6549): 	at kff.l(PG:132)
E/ExperimentLoader( 6549): 	at ieo.a(PG:43)
E/ExperimentLoader( 6549): 	at iep.a(PG:93)
E/ExperimentLoader( 6549): 	at fhn.a(PG:59)
E/ExperimentLoader( 6549): 	at lex.a(PG:85)
E/ExperimentLoader( 6549): 	at lex.b(PG:132)
E/ExperimentLoader( 6549): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6549): 	at fhk.a(PG:908)
E/ExperimentLoader( 6549): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6549): 	at ihi.a(PG:22)
E/ExperimentLoader( 6549): 	at kft.a(PG:91)
E/ExperimentLoader( 6549): 	at kfv.a(PG:62)
E/ExperimentLoader( 6549): 	... 12 more
E/ExperimentLoader( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6549): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6549): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6549): 	at ihi.a(PG:19)
E/ExperimentLoader( 6549): 	... 14 more
D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 6549): [getaccountstatus] Unexpected exception
E/HttpOperation( 6549): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6549): 	at kfv.a(PG:65)
E/HttpOperation( 6549): 	at kff.u(PG:385)
E/HttpOperation( 6549): 	at kfb.a(PG:29)
E/HttpOperation( 6549): 	at ixd.a(PG:248)
E/HttpOperation( 6549): 	at ixd.b(PG:206)
E/HttpOperation( 6549): 	at ixd.a(PG:175)
E/HttpOperation( 6549): 	at fig.a(PG:78)
E/HttpOperation( 6549): 	at lex.a(PG:85)
E/HttpOperation( 6549): 	at lex.b(PG:132)
E/HttpOperation( 6549): 	at fhk.a(PG:1146)
E/HttpOperation( 6549): 	at fhk.a(PG:908)
E/HttpOperation( 6549): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6549): 	at ihi.a(PG:22)
E/HttpOperation( 6549): 	at kft.a(PG:91)
E/HttpOperation( 6549): 	at kfv.a(PG:62)
E/HttpOperation( 6549): 	... 12 more
E/HttpOperation( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6549): 	at gde.c(Unknown Source)
E/HttpOperation( 6549): 	at gde.b(Unknown Source)
E/HttpOperation( 6549): 	at ihi.a(PG:19)
E/HttpOperation( 6549): 	... 14 more
,E/EsSyncAdapterService( 6549): Sync failure
E/EsSyncAdapterService( 6549): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6549): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6549): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6549): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6549): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6549): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6549): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6549): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6549): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6549): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6549): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6549): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6549): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6549): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6549): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6549): 	... 10 more
E/EsSyncAdapterService( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6549): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6549): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6549): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6549): 	... 12 more
E/EsSyncAdapterService( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6549): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6549): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6549): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6549): 	... 14 more
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SyncManager(  842): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 157349, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  842): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  842): mCursor = null
,E/SQLiteLog( 1638): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,V/AlarmManager(  842): waitForAlarm result :4
,D/KeyguardViewMediator( 1171): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/KeyguardViewMediator( 1171): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService(  842): [PWL] Off : 5s ago
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Watchdog(  842): !@Sync 5
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 310, PST = 349, CUR = 300,
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  842): [PWL] Off : 15s ago
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 310, PST = 344, CUR = 300
,V/AlarmManager(  842): waitForAlarm result :4
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): stay LED for fully charged
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
I/MotionRecognitionService(  842): Plugged
I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1638): Vacuum at: now=1454434054167 tag=VacuumService
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6579): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6579): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6579): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,V/AlarmManager(  842): waitForAlarm result :4
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GoogleURLConnFactory( 1638): Using platform SSLCertificateSocketFactory
,D/SSRM:m  (  842): SIOP:: AP = 310, PST = 334, CUR = 300
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/Uploader( 1638): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1638): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1638): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1638): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1638): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1638): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1638): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1638): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1638): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1638): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1638): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1638): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1638): (HTTPLog)-Thread-194-996350217: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/PowerManagerService(  842): [PWL] Off : 30s ago
,I/PowerManagerService(  842): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  842): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  842): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10012, pid=1638, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=195)
,I/qtaguid ( 1638): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1638, getuid(): 10012
,I/qtaguid ( 1638): Tagging socket 62 with tag 120100000000{4609,0} uid -1, pid: 1638, getuid(): 10012
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Uploader( 1638): No account for auth token provided
,I/qtaguid ( 1638): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1638, getuid(): 10012
,W/Uploader( 1638): No account for auth token provided
,I/qtaguid ( 1638): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1638, getuid(): 10012
,W/Uploader( 1638): No account for auth token provided
,I/qtaguid ( 1638): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1638, getuid(): 10012
,W/Uploader( 1638): No account for auth token provided
,I/qtaguid ( 1638): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1638, getuid(): 10012
,W/Uploader( 1638): No account for auth token provided
,I/qtaguid ( 1638): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1638, getuid(): 10012
,V/AlarmManager(  842): waitForAlarm result :4
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Uploader( 1638):  no longer exists, so no auth token.
,I/qtaguid ( 1638): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1638, getuid(): 10012
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7767): Starting books sync, d
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1638): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1638): creating new AssetManager and set to /system/app/Books/Books.apk
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
,D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7767): Authentication error
E/BooksAccountManager( 7767): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7767): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7767): null auth token
,I/qtaguid ( 7767): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7767, getuid(): 10082
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,I/qtaguid ( 7767): Untagging socket 34
,W/ApiaryClient( 7767): Error response from books API: {
W/ApiaryClient( 7767):  "error": {
W/ApiaryClient( 7767):   "errors": [
W/ApiaryClient( 7767):    {
W/ApiaryClient( 7767):     "domain": "global",
W/ApiaryClient( 7767):     "reason": "required",
W/ApiaryClient( 7767):     "message": "Login Required",
W/ApiaryClient( 7767):     "locationType": "header",
W/ApiaryClient( 7767):     "location": "Authorization"
W/ApiaryClient( 7767):    }
W/ApiaryClient( 7767):   ],
W/ApiaryClient( 7767):   "code": 401,
W/ApiaryClient( 7767):   "message": "Login Required"
W/ApiaryClient( 7767):  }
W/ApiaryClient( 7767): }
,W/ApiaryClient( 7767): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5544257535057048337&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7767): Headers suppressed
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7767): Authentication error
E/BooksAccountManager( 7767): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7767): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7767): null auth token
,I/qtaguid ( 7767): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7767, getuid(): 10082
,I/qtaguid ( 7767): Untagging socket 34
,W/ApiaryClient( 7767): Error response from books API: {
W/ApiaryClient( 7767):  "error": {
W/ApiaryClient( 7767):   "errors": [
W/ApiaryClient( 7767):    {
W/ApiaryClient( 7767):     "domain": "global",
W/ApiaryClient( 7767):     "reason": "required",
W/ApiaryClient( 7767):     "message": "Login Required",
W/ApiaryClient( 7767):     "locationType": "header",
W/ApiaryClient( 7767):     "location": "Authorization"
W/ApiaryClient( 7767):    }
W/ApiaryClient( 7767):   ],
W/ApiaryClient( 7767):   "code": 401,
W/ApiaryClient( 7767):   "message": "Login Required"
W/ApiaryClient( 7767):  }
W/ApiaryClient( 7767): }
,W/ApiaryClient( 7767): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5544257535057048337&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7767): Headers suppressed
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7767): Authentication error
E/BooksAccountManager( 7767): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7767): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7767): null auth token
,I/qtaguid ( 7767): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7767, getuid(): 10082
,I/qtaguid ( 7767): Untagging socket 34
,W/ApiaryClient( 7767): Error response from books API: {
W/ApiaryClient( 7767):  "error": {
W/ApiaryClient( 7767):   "errors": [
W/ApiaryClient( 7767):    {
W/ApiaryClient( 7767):     "domain": "global",
W/ApiaryClient( 7767):     "reason": "required",
W/ApiaryClient( 7767):     "message": "Login Required",
W/ApiaryClient( 7767):     "locationType": "header",
W/ApiaryClient( 7767):     "location": "Authorization"
W/ApiaryClient( 7767):    }
W/ApiaryClient( 7767):   ],
W/ApiaryClient( 7767):   "code": 401,
W/ApiaryClient( 7767):   "message": "Login Required"
W/ApiaryClient( 7767):  }
W/ApiaryClient( 7767): }
,W/ApiaryClient( 7767): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5544257535057048337&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7767): Headers suppressed
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/BooksSync( 7767): Soft error
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5544257535057048337&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7767): Headers suppressed
E/BooksSync( 7767): 
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7767): Sync error
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5544257535057048337&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7767): Headers suppressed
E/BooksSync( 7767): 
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7767): Finished books sync
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  842): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 159455, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  842): Explicit concurrent mark sweep GC freed 82483(4MB) AllocSpace objects, 35(1015KB) LOS objects, 30% free, 36MB/52MB, paused 1.716ms total 186.277ms
D/SecContentProvider2(  842): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  842): mCursor = null
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  842): !@Sync 6
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 300, PST = 324, CUR = 300
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,E/SMD     (  285): DCD ON,
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  842): [PWL] Off : 50s ago
,D/SSRM:m  (  842): SIOP:: AP = 300, PST = 318, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 300, PST = 314, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON,
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/Watchdog(  842): !@Sync 7
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 300, PST = 310, CUR = 300
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 1
I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  842): [PWL] Off : 75s ago
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  842): SIOP:: AP = 300, PST = 307, CUR = 300
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 304, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 3
,E/Watchdog(  842): !@Sync 8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 301, CUR = 300
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  842): [PWL] Off : 105s ago
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 299, CUR = 300
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 297, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  842): !@Sync 9
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  842): stay LED for fully charged
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 295, CUR = 300
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
,D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6549): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6549): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6549): 	at kfv.a(PG:65)
E/HttpOperation( 6549): 	at kff.u(PG:385)
E/HttpOperation( 6549): 	at kfb.a(PG:29)
E/HttpOperation( 6549): 	at kff.l(PG:132)
E/HttpOperation( 6549): 	at dsf.a(PG:807)
E/HttpOperation( 6549): 	at fhk.a(PG:1126)
E/HttpOperation( 6549): 	at fhk.a(PG:908)
E/HttpOperation( 6549): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6549): 	at ihi.a(PG:22)
E/HttpOperation( 6549): 	at kft.a(PG:91)
E/HttpOperation( 6549): 	at kfv.a(PG:62)
E/HttpOperation( 6549): 	... 8 more
E/HttpOperation( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6549): 	at gde.c(Unknown Source)
E/HttpOperation( 6549): 	at gde.b(Unknown Source)
E/HttpOperation( 6549): 	at ihi.a(PG:19)
E/HttpOperation( 6549): 	... 10 more
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
,D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true,
,E/SQLiteLog( 1638): (10) POSIX Error : 11 SQLite Error : 3850
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6549): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6549): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6549): 	at kfv.a(PG:65)
E/HttpOperation( 6549): 	at kff.u(PG:385)
E/HttpOperation( 6549): 	at kfb.a(PG:29)
E/HttpOperation( 6549): 	at kff.l(PG:132)
E/HttpOperation( 6549): 	at ieo.a(PG:43)
E/HttpOperation( 6549): 	at iep.a(PG:93)
E/HttpOperation( 6549): 	at fhn.a(PG:59)
E/HttpOperation( 6549): 	at lex.a(PG:85)
E/HttpOperation( 6549): 	at lex.b(PG:132)
E/HttpOperation( 6549): 	at fhk.a(PG:1146)
E/HttpOperation( 6549): 	at fhk.a(PG:908)
E/HttpOperation( 6549): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6549): 	at ihi.a(PG:22)
E/HttpOperation( 6549): 	at kft.a(PG:91)
E/HttpOperation( 6549): 	at kfv.a(PG:62)
E/HttpOperation( 6549): 	... 12 more
E/HttpOperation( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6549): 	at gde.c(Unknown Source)
E/HttpOperation( 6549): 	at gde.b(Unknown Source)
E/HttpOperation( 6549): 	at ihi.a(PG:19)
E/HttpOperation( 6549): 	... 14 more
,E/ExperimentLoader( 6549): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6549): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6549): 	at kfv.a(PG:65)
E/ExperimentLoader( 6549): 	at kff.u(PG:385)
E/ExperimentLoader( 6549): 	at kfb.a(PG:29)
E/ExperimentLoader( 6549): 	at kff.l(PG:132)
E/ExperimentLoader( 6549): 	at ieo.a(PG:43)
E/ExperimentLoader( 6549): 	at iep.a(PG:93)
E/ExperimentLoader( 6549): 	at fhn.a(PG:59)
E/ExperimentLoader( 6549): 	at lex.a(PG:85)
E/ExperimentLoader( 6549): 	at lex.b(PG:132)
E/ExperimentLoader( 6549): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6549): 	at fhk.a(PG:908)
E/ExperimentLoader( 6549): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6549): 	at ihi.a(PG:22)
E/ExperimentLoader( 6549): 	at kft.a(PG:91)
E/ExperimentLoader( 6549): 	at kfv.a(PG:62)
E/ExperimentLoader( 6549): 	... 12 more
E/ExperimentLoader( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6549): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6549): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6549): 	at ihi.a(PG:19)
E/ExperimentLoader( 6549): 	... 14 more
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6549): [getaccountstatus] Unexpected exception
E/HttpOperation( 6549): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6549): 	at kfv.a(PG:65)
E/HttpOperation( 6549): 	at kff.u(PG:385)
E/HttpOperation( 6549): 	at kfb.a(PG:29)
E/HttpOperation( 6549): 	at ixd.a(PG:248)
E/HttpOperation( 6549): 	at ixd.b(PG:206)
E/HttpOperation( 6549): 	at ixd.a(PG:175)
E/HttpOperation( 6549): 	at fig.a(PG:78)
E/HttpOperation( 6549): 	at lex.a(PG:85)
E/HttpOperation( 6549): 	at lex.b(PG:132)
E/HttpOperation( 6549): 	at fhk.a(PG:1146)
E/HttpOperation( 6549): 	at fhk.a(PG:908)
E/HttpOperation( 6549): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6549): 	at ihi.a(PG:22)
E/HttpOperation( 6549): 	at kft.a(PG:91)
E/HttpOperation( 6549): 	at kfv.a(PG:62)
E/HttpOperation( 6549): 	... 12 more
E/HttpOperation( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6549): 	at gde.c(Unknown Source)
E/HttpOperation( 6549): 	at gde.b(Unknown Source)
E/HttpOperation( 6549): 	at ihi.a(PG:19)
E/HttpOperation( 6549): 	... 14 more
,E/EsSyncAdapterService( 6549): Sync failure
E/EsSyncAdapterService( 6549): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6549): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6549): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6549): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6549): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6549): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6549): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6549): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6549): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6549): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6549): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6549): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6549): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6549): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6549): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6549): 	... 10 more
E/EsSyncAdapterService( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6549): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6549): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6549): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6549): 	... 12 more
E/EsSyncAdapterService( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6549): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6549): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6549): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6549): 	... 14 more
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  842): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 286597, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  842): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  842): mCursor = null
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1638): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/PowerManagerService(  842): [PWL] Off : 140s ago
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 294, CUR = 300
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 293, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/TimaService(  842): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  842): TimaServiceHandler.handleMessage what =1
,D/TimaService(  842): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  842): initializing...
,I/TLC_TIMA_PKM_initialize(  842): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  842): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  842): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  842): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  842): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  842): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  842): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  842): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  842): App is not loaded in QSEE
,D/QSEECOMAPI: (  842): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  842): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  842): Trustlet response is completed
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  842): !@Sync 10
,E/SMD     (  285): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  842): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  842): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  842): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  842): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :4
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  842): stay LED for fully charged
D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
I/MotionRecognitionService(  842): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 292, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager(  842): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  842): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8433): MountEmulatedStorage()
,E/Zygote  ( 8433): v2
I/libpersona( 8433): KNOX_SDCARD checking this for 10081
I/libpersona( 8433): KNOX_SDCARD not a persona
,I/ActivityManager(  842): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8433 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8433): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8433): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8433): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 8433): TimaSignature is unavailable
,D/ActivityThread( 8433): Added TimaKeyStore provider
,D/ResourcesManager( 8433): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  842): Killing 6621:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,W/libprocessgroup(  842): failed to open /acct/uid_10012/pid_6621/cgroup.procs: No such file or directory
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  842): [PWL] Off : 180s ago
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...,
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  842): !@Sync 11
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :4
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  842): stay LED for fully charged
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
I/MotionRecognitionService(  842): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7767): Starting books sync, d
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7767): Authentication error
E/BooksAccountManager( 7767): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7767): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7767): null auth token
,I/qtaguid ( 7767): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7767, getuid(): 10082
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,I/qtaguid ( 7767): Untagging socket 34
,W/ApiaryClient( 7767): Error response from books API: {
W/ApiaryClient( 7767):  "error": {
W/ApiaryClient( 7767):   "errors": [
W/ApiaryClient( 7767):    {
W/ApiaryClient( 7767):     "domain": "global",
W/ApiaryClient( 7767):     "reason": "required",
W/ApiaryClient( 7767):     "message": "Login Required",
W/ApiaryClient( 7767):     "locationType": "header",
W/ApiaryClient( 7767):     "location": "Authorization"
W/ApiaryClient( 7767):    }
W/ApiaryClient( 7767):   ],
W/ApiaryClient( 7767):   "code": 401,
W/ApiaryClient( 7767):   "message": "Login Required"
W/ApiaryClient( 7767):  }
W/ApiaryClient( 7767): }
,W/ApiaryClient( 7767): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5776897348603322709&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7767): Headers suppressed
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7767): Authentication error
E/BooksAccountManager( 7767): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7767): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7767): null auth token
,I/qtaguid ( 7767): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7767, getuid(): 10082
,I/qtaguid ( 7767): Untagging socket 34
,W/ApiaryClient( 7767): Error response from books API: {
W/ApiaryClient( 7767):  "error": {
W/ApiaryClient( 7767):   "errors": [
W/ApiaryClient( 7767):    {
W/ApiaryClient( 7767):     "domain": "global",
W/ApiaryClient( 7767):     "reason": "required",
W/ApiaryClient( 7767):     "message": "Login Required",
W/ApiaryClient( 7767):     "locationType": "header",
W/ApiaryClient( 7767):     "location": "Authorization"
W/ApiaryClient( 7767):    }
W/ApiaryClient( 7767):   ],
W/ApiaryClient( 7767):   "code": 401,
W/ApiaryClient( 7767):   "message": "Login Required"
W/ApiaryClient( 7767):  }
W/ApiaryClient( 7767): }
,W/ApiaryClient( 7767): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5776897348603322709&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7767): Headers suppressed
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7767): Authentication error
E/BooksAccountManager( 7767): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7767): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7767): null auth token
,I/qtaguid ( 7767): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7767, getuid(): 10082
,I/qtaguid ( 7767): Untagging socket 34
,W/ApiaryClient( 7767): Error response from books API: {
W/ApiaryClient( 7767):  "error": {
W/ApiaryClient( 7767):   "errors": [
W/ApiaryClient( 7767):    {
W/ApiaryClient( 7767):     "domain": "global",
W/ApiaryClient( 7767):     "reason": "required",
W/ApiaryClient( 7767):     "message": "Login Required",
W/ApiaryClient( 7767):     "locationType": "header",
W/ApiaryClient( 7767):     "location": "Authorization"
W/ApiaryClient( 7767):    }
W/ApiaryClient( 7767):   ],
W/ApiaryClient( 7767):   "code": 401,
W/ApiaryClient( 7767):   "message": "Login Required"
W/ApiaryClient( 7767):  }
W/ApiaryClient( 7767): }
,W/ApiaryClient( 7767): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5776897348603322709&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7767): Headers suppressed
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/BooksSync( 7767): Soft error
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5776897348603322709&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7767): Headers suppressed
E/BooksSync( 7767): 
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7767): Sync error
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=5776897348603322709&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7767): Headers suppressed
E/BooksSync( 7767): 
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7767): Finished books sync
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  842): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 317167, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  842): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  842): mCursor = null
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1638): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 6579): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6579): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6579): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6579): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6579): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6579): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6579): 	at android.os.Binder.execTransact(Binder.java:446)
,I/art     ( 1638): Explicit concurrent mark sweep GC freed 64291(3MB) AllocSpace objects, 76(5MB) LOS objects, 40% free, 18MB/30MB, paused 655us total 45.828ms
,W/System  ( 6579): Ignoring header User-Agent because its value was null.
,I/System.out( 6579): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6579): (HTTPLog)-Static: isShipBuild true
I/System.out( 6579): (HTTPLog)-Thread-1083-425731685: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0,
D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000,
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  285): DCD ON
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  842): !@Sync 12
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :4
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  842): stay LED for fully charged
D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
I/MotionRecognitionService(  842): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  842): [PWL] Off : 225s ago
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,V/AlarmManager(  842): waitForAlarm result :8
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  842): !@Sync 13
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  842): [PWL] Off : 275s ago
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  842): !@Sync 14
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  842): !@Sync 15
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,D/BatteryService(  842): stay LED for fully charged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/bootchecker(  323): bootchecker wake up!!
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/PowerManagerService(  842): [PWL] Off : 330s ago
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  842): !@Sync 16
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  842): !@Sync 17
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  842): stay LED for fully charged
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1638): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
D/SecContentProvider2(  842): mCursor = null
,D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6549): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6549): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6549): 	at kfv.a(PG:65)
E/HttpOperation( 6549): 	at kff.u(PG:385)
E/HttpOperation( 6549): 	at kfb.a(PG:29)
E/HttpOperation( 6549): 	at kff.l(PG:132)
E/HttpOperation( 6549): 	at dsf.a(PG:807)
E/HttpOperation( 6549): 	at fhk.a(PG:1126)
E/HttpOperation( 6549): 	at fhk.a(PG:908)
E/HttpOperation( 6549): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6549): 	at ihi.a(PG:22)
E/HttpOperation( 6549): 	at kft.a(PG:91)
E/HttpOperation( 6549): 	at kfv.a(PG:62)
E/HttpOperation( 6549): 	... 8 more
E/HttpOperation( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6549): 	at gde.c(Unknown Source)
E/HttpOperation( 6549): 	at gde.b(Unknown Source)
E/HttpOperation( 6549): 	at ihi.a(PG:19)
E/HttpOperation( 6549): 	... 10 more
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
,D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/HttpOperation( 6549): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6549): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6549): 	at kfv.a(PG:65)
E/HttpOperation( 6549): 	at kff.u(PG:385)
E/HttpOperation( 6549): 	at kfb.a(PG:29)
E/HttpOperation( 6549): 	at kff.l(PG:132)
E/HttpOperation( 6549): 	at ieo.a(PG:43)
E/HttpOperation( 6549): 	at iep.a(PG:93)
E/HttpOperation( 6549): 	at fhn.a(PG:59)
E/HttpOperation( 6549): 	at lex.a(PG:85)
E/HttpOperation( 6549): 	at lex.b(PG:132)
E/HttpOperation( 6549): 	at fhk.a(PG:1146)
E/HttpOperation( 6549): 	at fhk.a(PG:908)
E/HttpOperation( 6549): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6549): 	at ihi.a(PG:22)
E/HttpOperation( 6549): 	at kft.a(PG:91)
E/HttpOperation( 6549): 	at kfv.a(PG:62)
E/HttpOperation( 6549): 	... 12 more
E/HttpOperation( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6549): 	at gde.c(Unknown Source)
E/HttpOperation( 6549): 	at gde.b(Unknown Source)
E/HttpOperation( 6549): 	at ihi.a(PG:19)
E/HttpOperation( 6549): 	... 14 more
,E/ExperimentLoader( 6549): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6549): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6549): 	at kfv.a(PG:65)
E/ExperimentLoader( 6549): 	at kff.u(PG:385)
E/ExperimentLoader( 6549): 	at kfb.a(PG:29)
E/ExperimentLoader( 6549): 	at kff.l(PG:132)
E/ExperimentLoader( 6549): 	at ieo.a(PG:43)
E/ExperimentLoader( 6549): 	at iep.a(PG:93)
E/ExperimentLoader( 6549): 	at fhn.a(PG:59)
E/ExperimentLoader( 6549): 	at lex.a(PG:85)
E/ExperimentLoader( 6549): 	at lex.b(PG:132)
E/ExperimentLoader( 6549): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6549): 	at fhk.a(PG:908)
E/ExperimentLoader( 6549): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6549): 	at ihi.a(PG:22)
E/ExperimentLoader( 6549): 	at kft.a(PG:91)
E/ExperimentLoader( 6549): 	at kfv.a(PG:62)
E/ExperimentLoader( 6549): 	... 12 more
E/ExperimentLoader( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6549): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6549): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6549): 	at ihi.a(PG:19)
E/ExperimentLoader( 6549): 	... 14 more
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/SQLiteLog( 1638): (10) POSIX Error : 11 SQLite Error : 3850
,I/PowerManagerService(  842): [PWL] Off : 390s ago
I/PowerManagerService(  842): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  842): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  842): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.plus.content.EsProvider/com.google/eM_ADDR' (uid=1000, pid=842, ws=WorkSource{10135}) (elapsedTime=727)
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6549): [getaccountstatus] Unexpected exception
E/HttpOperation( 6549): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6549): 	at kfv.a(PG:65)
E/HttpOperation( 6549): 	at kff.u(PG:385)
E/HttpOperation( 6549): 	at kfb.a(PG:29)
E/HttpOperation( 6549): 	at ixd.a(PG:248)
E/HttpOperation( 6549): 	at ixd.b(PG:206)
E/HttpOperation( 6549): 	at ixd.a(PG:175)
E/HttpOperation( 6549): 	at fig.a(PG:78)
E/HttpOperation( 6549): 	at lex.a(PG:85)
E/HttpOperation( 6549): 	at lex.b(PG:132)
E/HttpOperation( 6549): 	at fhk.a(PG:1146)
E/HttpOperation( 6549): 	at fhk.a(PG:908)
E/HttpOperation( 6549): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6549): 	at ihi.a(PG:22)
E/HttpOperation( 6549): 	at kft.a(PG:91)
E/HttpOperation( 6549): 	at kfv.a(PG:62)
E/HttpOperation( 6549): 	... 12 more
E/HttpOperation( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6549): 	at gde.c(Unknown Source)
E/HttpOperation( 6549): 	at gde.b(Unknown Source)
E/HttpOperation( 6549): 	at ihi.a(PG:19)
E/HttpOperation( 6549): 	... 14 more
,E/EsSyncAdapterService( 6549): Sync failure
E/EsSyncAdapterService( 6549): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6549): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6549): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6549): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6549): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6549): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6549): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6549): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6549): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6549): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6549): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6549): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6549): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6549): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6549): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6549): 	... 10 more
E/EsSyncAdapterService( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6549): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6549): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6549): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6549): 	... 12 more
E/EsSyncAdapterService( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6549): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6549): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6549): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6549): 	... 14 more
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  842): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 545553, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  842): Explicit concurrent mark sweep GC freed 63975(4MB) AllocSpace objects, 118(2MB) LOS objects, 30% free, 36MB/52MB, paused 1.688ms total 129.657ms
,D/SecContentProvider2(  842): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  842): mCursor = null
,E/SQLiteLog( 1638): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  842): !@Sync 18
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/Atfwd_Daemon(  332): Stop the daemon....
,E/Watchdog(  842): !@Sync 19
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :4
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): stay LED for fully charged
D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
I/MotionRecognitionService(  842): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7767): Starting books sync, d
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1638): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
,D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7767): Authentication error
E/BooksAccountManager( 7767): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7767): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7767): null auth token
,I/qtaguid ( 7767): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7767, getuid(): 10082
,I/qtaguid ( 7767): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7767, getuid(): 10082
,I/qtaguid ( 7767): Untagging socket 34
,W/ApiaryClient( 7767): Error response from books API: {
W/ApiaryClient( 7767):  "error": {
W/ApiaryClient( 7767):   "errors": [
W/ApiaryClient( 7767):    {
W/ApiaryClient( 7767):     "domain": "global",
W/ApiaryClient( 7767):     "reason": "required",
W/ApiaryClient( 7767):     "message": "Login Required",
W/ApiaryClient( 7767):     "locationType": "header",
W/ApiaryClient( 7767):     "location": "Authorization"
W/ApiaryClient( 7767):    }
W/ApiaryClient( 7767):   ],
W/ApiaryClient( 7767):   "code": 401,
W/ApiaryClient( 7767):   "message": "Login Required"
W/ApiaryClient( 7767):  }
W/ApiaryClient( 7767): }
,W/ApiaryClient( 7767): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-693505294135063767&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7767): Headers suppressed
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7767): Authentication error
E/BooksAccountManager( 7767): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7767): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7767): null auth token
,I/qtaguid ( 7767): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7767, getuid(): 10082
,I/qtaguid ( 7767): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7767, getuid(): 10082
,I/qtaguid ( 7767): Untagging socket 34
,W/ApiaryClient( 7767): Error response from books API: {
W/ApiaryClient( 7767):  "error": {
W/ApiaryClient( 7767):   "errors": [
W/ApiaryClient( 7767):    {
W/ApiaryClient( 7767):     "domain": "global",
W/ApiaryClient( 7767):     "reason": "required",
W/ApiaryClient( 7767):     "message": "Login Required",
W/ApiaryClient( 7767):     "locationType": "header",
W/ApiaryClient( 7767):     "location": "Authorization"
W/ApiaryClient( 7767):    }
W/ApiaryClient( 7767):   ],
W/ApiaryClient( 7767):   "code": 401,
W/ApiaryClient( 7767):   "message": "Login Required"
W/ApiaryClient( 7767):  }
W/ApiaryClient( 7767): }
W/ApiaryClient( 7767): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-693505294135063767&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7767): Headers suppressed
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1638): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7767): Authentication error
E/BooksAccountManager( 7767): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7767): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7767): null auth token
,I/qtaguid ( 7767): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7767, getuid(): 10082
,I/qtaguid ( 7767): Untagging socket 34
,W/ApiaryClient( 7767): Error response from books API: {
W/ApiaryClient( 7767):  "error": {
W/ApiaryClient( 7767):   "errors": [
W/ApiaryClient( 7767):    {
W/ApiaryClient( 7767):     "domain": "global",
W/ApiaryClient( 7767):     "reason": "required",
W/ApiaryClient( 7767):     "message": "Login Required",
W/ApiaryClient( 7767):     "locationType": "header",
W/ApiaryClient( 7767):     "location": "Authorization"
W/ApiaryClient( 7767):    }
W/ApiaryClient( 7767):   ],
W/ApiaryClient( 7767):   "code": 401,
W/ApiaryClient( 7767):   "message": "Login Required"
W/ApiaryClient( 7767):  }
W/ApiaryClient( 7767): }
,W/ApiaryClient( 7767): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-693505294135063767&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7767): Headers suppressed
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7767): Soft error
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-693505294135063767&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7767): Headers suppressed
E/BooksSync( 7767): 
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7767): Sync error
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-693505294135063767&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7767): Headers suppressed
E/BooksSync( 7767): 
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7767): Finished books sync
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  842): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 602581, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2(  842): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  842): mCursor = null
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/TimaService(  842): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  842): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  842): TimaServiceHandler.handleMessage what =1
,I/PowerManagerService(  842): [PWL] Off : 455s ago
,I/PowerManagerService(  842): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  842): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  842): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=842, ws=null) (elapsedTime=606)
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog(  842): !@Sync 20
,E/SMD     (  285): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  842): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  842): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  842): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  842): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/ActivityManager(  842): Killing 7028:com.samsung.android.provider.shootingmodeprovider/u0a170 (adj 15): bgCount ##41
,W/libprocessgroup(  842): failed to open /acct/uid_10170/pid_7028/cgroup.procs: No such file or directory
,V/AlarmManager(  842): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  842): stay LED for fully charged
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
I/MotionRecognitionService(  842): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  842): !@Sync 21
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON,
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  842): !@Sync 22
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  842): [PWL] Off : 525s ago
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  842): !@Sync 23
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  842): !@Sync 24
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,D/BatteryService(  842): stay LED for fully charged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  842): [PWL] Off : 600s ago
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  842): !@Sync 25
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 280, PST = 289, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  842): !@Sync 26
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 280, PST = 288, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 280, PST = 287, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 280, PST = 286, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  842): !@Sync 27
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 284, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  842): [PWL] Off : 680s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 282, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 280, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  842): !@Sync 28
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 278, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 276, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  842): !@Sync 29
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  285): DCD ON
,D/TimaService(  842): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  842): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  842): TimaServiceHandler.handleMessage what =1
,E/Watchdog(  842): !@Sync 30
,E/SMD     (  285): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  842): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  842): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  842): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  842): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 272, CUR = 300
,I/PowerManagerService(  842): [PWL] Off : 765s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,E/SMD     (  285): DCD ON
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  842): SIOP:: AP = 280, PST = 273, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,D/BatteryService(  842): stay LED for fully charged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  842): !@Sync 31
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  842): !@Sync 32
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/LightsService(  842): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,E/LightSensor(  842): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/Finsky  ( 6579): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/SensorManager(  842): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/Finsky  ( 6579): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/GCM     ( 1638): Message class com.google.f.a.a.i
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 2472): Aggregate from 1454432807163 (log), 1454432807163 (data)
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  842): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  842): [SvcLED]  onSensorChanged::light value = 0
E/LightSensor(  842): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,W/Finsky  ( 6579): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/SensorManager(  842): unregisterListener ::   
D/LightsService(  842): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6579): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6579): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6579): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6579): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/DeviceConnectionService( 2197): client connected with version: 7571000
,D/SSRM:m  (  842): SIOP:: AP = 290, PST = 275, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  842): !@Sync 33
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 275, CUR = 300
,I/PowerManagerService(  842): [PWL] Off : 855s ago
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :4
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  842): stay LED for fully charged
D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
I/MotionRecognitionService(  842): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6579): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6579): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6579): [1] 5.onFinished: Scheduling replication attempt 1.
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 280, PST = 274, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 273, CUR = 300
,E/Watchdog(  842): !@Sync 34
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :4
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  842): stay LED for fully charged
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
I/MotionRecognitionService(  842): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6579): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6579): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6579): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  842): stay LED for fully charged
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/art     (  842): Explicit concurrent mark sweep GC freed 59076(4MB) AllocSpace objects, 159(2MB) LOS objects, 30% free, 36MB/52MB, paused 1.735ms total 186.713ms
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6579): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6579): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6579): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 280, PST = 274, CUR = 300
,V/AlarmManager(  842): waitForAlarm result :4
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1638): Explicit concurrent mark sweep GC freed 36218(2MB) AllocSpace objects, 14(1134KB) LOS objects, 39% free, 18MB/30MB, paused 918us total 37.813ms
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1638): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
,D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 6549): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 6549): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6549): 	at kfv.a(PG:65)
E/HttpOperation( 6549): 	at kff.u(PG:385)
E/HttpOperation( 6549): 	at kfb.a(PG:29)
E/HttpOperation( 6549): 	at kff.l(PG:132)
E/HttpOperation( 6549): 	at dsf.a(PG:807)
E/HttpOperation( 6549): 	at fhk.a(PG:1126)
E/HttpOperation( 6549): 	at fhk.a(PG:908)
E/HttpOperation( 6549): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6549): 	at ihi.a(PG:22)
E/HttpOperation( 6549): 	at kft.a(PG:91)
E/HttpOperation( 6549): 	at kfv.a(PG:62)
E/HttpOperation( 6549): 	... 8 more
E/HttpOperation( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6549): 	at gde.c(Unknown Source)
E/HttpOperation( 6549): 	at gde.b(Unknown Source)
E/HttpOperation( 6549): 	at ihi.a(PG:19)
E/HttpOperation( 6549): 	... 10 more
I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
,D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6549): [getmobileexperiments] Unexpected exception
E/HttpOperation( 6549): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6549): 	at kfv.a(PG:65)
E/HttpOperation( 6549): 	at kff.u(PG:385)
E/HttpOperation( 6549): 	at kfb.a(PG:29)
E/HttpOperation( 6549): 	at kff.l(PG:132)
E/HttpOperation( 6549): 	at ieo.a(PG:43)
E/HttpOperation( 6549): 	at iep.a(PG:93)
E/HttpOperation( 6549): 	at fhn.a(PG:59)
E/HttpOperation( 6549): 	at lex.a(PG:85)
E/HttpOperation( 6549): 	at lex.b(PG:132)
E/HttpOperation( 6549): 	at fhk.a(PG:1146)
E/HttpOperation( 6549): 	at fhk.a(PG:908)
E/HttpOperation( 6549): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6549): 	at ihi.a(PG:22)
E/HttpOperation( 6549): 	at kft.a(PG:91)
E/HttpOperation( 6549): 	at kfv.a(PG:62)
E/HttpOperation( 6549): 	... 12 more
E/HttpOperation( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6549): 	at gde.c(Unknown Source)
E/HttpOperation( 6549): 	at gde.b(Unknown Source)
E/HttpOperation( 6549): 	at ihi.a(PG:19)
E/HttpOperation( 6549): 	... 14 more
,E/ExperimentLoader( 6549): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6549): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 6549): 	at kfv.a(PG:65)
E/ExperimentLoader( 6549): 	at kff.u(PG:385)
E/ExperimentLoader( 6549): 	at kfb.a(PG:29)
E/ExperimentLoader( 6549): 	at kff.l(PG:132)
E/ExperimentLoader( 6549): 	at ieo.a(PG:43)
E/ExperimentLoader( 6549): 	at iep.a(PG:93)
E/ExperimentLoader( 6549): 	at fhn.a(PG:59)
E/ExperimentLoader( 6549): 	at lex.a(PG:85)
E/ExperimentLoader( 6549): 	at lex.b(PG:132)
E/ExperimentLoader( 6549): 	at fhk.a(PG:1146)
E/ExperimentLoader( 6549): 	at fhk.a(PG:908)
E/ExperimentLoader( 6549): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 6549): 	at ihi.a(PG:22)
E/ExperimentLoader( 6549): 	at kft.a(PG:91)
E/ExperimentLoader( 6549): 	at kfv.a(PG:62)
E/ExperimentLoader( 6549): 	... 12 more
E/ExperimentLoader( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 6549): 	at gde.c(Unknown Source)
E/ExperimentLoader( 6549): 	at gde.b(Unknown Source)
E/ExperimentLoader( 6549): 	at ihi.a(PG:19)
E/ExperimentLoader( 6549): 	... 14 more
,E/SQLiteLog( 1638): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,E/HttpOperation( 6549): [getaccountstatus] Unexpected exception
E/HttpOperation( 6549): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 6549): 	at kfv.a(PG:65)
E/HttpOperation( 6549): 	at kff.u(PG:385)
E/HttpOperation( 6549): 	at kfb.a(PG:29)
E/HttpOperation( 6549): 	at ixd.a(PG:248)
E/HttpOperation( 6549): 	at ixd.b(PG:206)
E/HttpOperation( 6549): 	at ixd.a(PG:175)
E/HttpOperation( 6549): 	at fig.a(PG:78)
E/HttpOperation( 6549): 	at lex.a(PG:85)
E/HttpOperation( 6549): 	at lex.b(PG:132)
E/HttpOperation( 6549): 	at fhk.a(PG:1146)
E/HttpOperation( 6549): 	at fhk.a(PG:908)
E/HttpOperation( 6549): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 6549): 	at ihi.a(PG:22)
E/HttpOperation( 6549): 	at kft.a(PG:91)
E/HttpOperation( 6549): 	at kfv.a(PG:62)
E/HttpOperation( 6549): 	... 12 more
E/HttpOperation( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 6549): 	at gde.c(Unknown Source)
E/HttpOperation( 6549): 	at gde.b(Unknown Source)
E/HttpOperation( 6549): 	at ihi.a(PG:19)
E/HttpOperation( 6549): 	... 14 more
,E/EsSyncAdapterService( 6549): Sync failure
E/EsSyncAdapterService( 6549): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 6549): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 6549): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 6549): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 6549): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 6549): 	at fig.a(PG:78)
E/EsSyncAdapterService( 6549): 	at lex.a(PG:85)
E/EsSyncAdapterService( 6549): 	at lex.b(PG:132)
E/EsSyncAdapterService( 6549): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 6549): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 6549): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 6549): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 6549): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 6549): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 6549): 	at kff.u(PG:385)
E/EsSyncAdapterService( 6549): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 6549): 	... 10 more
E/EsSyncAdapterService( 6549): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 6549): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 6549): 	at kft.a(PG:91)
E/EsSyncAdapterService( 6549): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 6549): 	... 12 more
E/EsSyncAdapterService( 6549): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 6549): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 6549): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 6549): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 6549): 	... 14 more
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  842): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1062461, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ResourcesManager( 2850): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2850): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  842): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  842): mCursor = null
,E/Watchdog(  842): !@Sync 35
,E/SMD     (  285): DCD ON
,E/SQLiteLog( 1638): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 280, PST = 275, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :4
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6579): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6579): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6579): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 280, PST = 276, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 276, CUR = 300
,V/AlarmManager(  842): waitForAlarm result :4
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  842): stay LED for fully charged
D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
I/MotionRecognitionService(  842): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  842): !@Sync 36
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :4
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6579): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6579): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6579): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :8
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,D/BatteryService(  842): stay LED for fully charged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  842): [PWL] Off : 950s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  842): stay LED for fully charged
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
I/MotionRecognitionService(  842): setPowerConnected  = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6579): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6579): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6579): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 273, CUR = 300
,V/AlarmManager(  842): waitForAlarm result :4
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7767): Starting books sync, d
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1638): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7767): Authentication error
E/BooksAccountManager( 7767): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7767): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7767): null auth token
,I/qtaguid ( 7767): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7767, getuid(): 10082
,I/qtaguid ( 7767): Untagging socket 34
,W/ApiaryClient( 7767): Error response from books API: {
W/ApiaryClient( 7767):  "error": {
W/ApiaryClient( 7767):   "errors": [
W/ApiaryClient( 7767):    {
W/ApiaryClient( 7767):     "domain": "global",
W/ApiaryClient( 7767):     "reason": "required",
W/ApiaryClient( 7767):     "message": "Login Required",
W/ApiaryClient( 7767):     "locationType": "header",
W/ApiaryClient( 7767):     "location": "Authorization"
W/ApiaryClient( 7767):    }
W/ApiaryClient( 7767):   ],
W/ApiaryClient( 7767):   "code": 401,
W/ApiaryClient( 7767):   "message": "Login Required"
W/ApiaryClient( 7767):  }
W/ApiaryClient( 7767): }
,W/ApiaryClient( 7767): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1589709436088137646&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7767): Headers suppressed
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  842): !@Sync 37
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7767): Authentication error
E/BooksAccountManager( 7767): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7767): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7767): null auth token
,I/qtaguid ( 7767): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7767, getuid(): 10082
,I/qtaguid ( 7767): Tagging socket 40 with tag 10000000000{256,0} uid -1, pid: 7767, getuid(): 10082
,I/qtaguid ( 7767): Untagging socket 34
,W/ApiaryClient( 7767): Error response from books API: {
W/ApiaryClient( 7767):  "error": {
W/ApiaryClient( 7767):   "errors": [
W/ApiaryClient( 7767):    {
W/ApiaryClient( 7767):     "domain": "global",
W/ApiaryClient( 7767):     "reason": "required",
W/ApiaryClient( 7767):     "message": "Login Required",
W/ApiaryClient( 7767):     "locationType": "header",
W/ApiaryClient( 7767):     "location": "Authorization"
W/ApiaryClient( 7767):    }
W/ApiaryClient( 7767):   ],
W/ApiaryClient( 7767):   "code": 401,
W/ApiaryClient( 7767):   "message": "Login Required"
W/ApiaryClient( 7767):  }
W/ApiaryClient( 7767): }
,W/ApiaryClient( 7767): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1589709436088137646&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7767): Headers suppressed
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1638): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1638): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1638): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1638): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1638): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1638): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  842): uri = 14 selection = getSealedState
,D/SecContentProvider2(  842): mCursor = null
D/SecContentProvider2(  842): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  842): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  842): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1171): Icon Only
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): There is/are notification(s) 
,W/GLSActivity( 1638): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1638): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1638): 	,at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1638): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1638): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1638): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1638): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7767): Authentication error
E/BooksAccountManager( 7767): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7767): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7767): null auth token
,I/qtaguid ( 7767): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7767, getuid(): 10082
,I/qtaguid ( 7767): Untagging socket 34
,W/ApiaryClient( 7767): Error response from books API: {
W/ApiaryClient( 7767):  "error": {
W/ApiaryClient( 7767):   "errors": [
W/ApiaryClient( 7767):    {
W/ApiaryClient( 7767):     "domain": "global",
W/ApiaryClient( 7767):     "reason": "required",
W/ApiaryClient( 7767):     "message": "Login Required",
W/ApiaryClient( 7767):     "locationType": "header",
W/ApiaryClient( 7767):     "location": "Authorization"
W/ApiaryClient( 7767):    }
W/ApiaryClient( 7767):   ],
W/ApiaryClient( 7767):   "code": 401,
W/ApiaryClient( 7767):   "message": "Login Required"
W/ApiaryClient( 7767):  }
W/ApiaryClient( 7767): }
,W/ApiaryClient( 7767): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1589709436088137646&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7767): Headers suppressed
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/BooksSync( 7767): Soft error
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1589709436088137646&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7767): Headers suppressed
E/BooksSync( 7767): 
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7767): Sync error
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7767): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-1589709436088137646&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7767): Headers suppressed
E/BooksSync( 7767): 
E/BooksSync( 7767): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7767): Finished books sync
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  842): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1113440, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  842): Explicit concurrent mark sweep GC freed 40341(2MB) AllocSpace objects, 28(838KB) LOS objects, 30% free, 36MB/52MB, paused 1.630ms total 129.214ms
,D/SecContentProvider2(  842): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  842): mCursor = null
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 280, PST = 274, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 274, CUR = 300
,V/AlarmManager(  842): waitForAlarm result :4
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  842): stay LED for fully charged
D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
I/MotionRecognitionService(  842): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  842): !@Sync 38
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  842): waitForAlarm result :8
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 272, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON,
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 271, CUR = 300
,E/Watchdog(  842): !@Sync 39
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  842): [PWL] Off : 1050s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/TimaService(  842): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  842): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  842): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  842): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  842): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  842): Updating Usage Statistics in DB @ 1454435088389
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 271, CUR = 300
,I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
,W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
,W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
,W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
,W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
,W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
,W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
,W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
,W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  842): ::getAppControlDB: Exception to create DB
,W/System.err(  842): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  842): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  842): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsage(  842): Done Updating Usage Statistics in DB @ 1454435088652
,E/Watchdog(  842): !@Sync 40
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel(  842): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  842): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  842): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  842): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 280, PST = 272, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 271, CUR = 300
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 271, CUR = 300
,E/Watchdog(  842): !@Sync 41
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 271, CUR = 300
,D/ConnectivityService(  842): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 271, CUR = 300
,E/Watchdog(  842): !@Sync 42
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  842): SIOP:: AP = 270, PST = 271, CUR = 300
,D/BatteryService(  842): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  842): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  842): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  842):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  842): Plugged
,I/MotionRecognitionService(  842): setPowerConnected  = true
,D/BatteryService(  842): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3252): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3252): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1200000ms),E/SMD     (  285): DCD ON
D/AndroidRuntime( 8746): 
D/AndroidRuntime( 8746): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8746): CheckJNI is OFF
D/AndroidRuntime( 8746): setted country_code = Germany
D/AndroidRuntime( 8746): setted countryiso_code = DE
D/AndroidRuntime( 8746): setted sales_code = DBT
D/AndroidRuntime( 8746): readGMSProperty: start
D/AndroidRuntime( 8746): readGMSProperty: already setted!!
D/AndroidRuntime( 8746): readGMSProperty: end
D/AndroidRuntime( 8746): addProductProperty: start
E/AffinityControl( 8746): AffinityControl: registerfunction enter
D/AndroidRuntime( 8746): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService(  842): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  842): START PACKAGE DELETE: observer{790987011}
D/PackageManager(  842): pkg{<packageName>}
D/PackageManager(  842): user{0}
D/PackageManager(  842): caller{2000}
D/PackageManager(  842): flags{3}
D/PersonaManagerService(  842): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  842): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  842): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  842): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  842): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  842): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  842): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  842): getApplicationUninstallationEnabled
D/ApplicationPolicy(  842): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  842): !@killApplicatoin: 10200, uninstall pkg
I/ActivityManager(  842): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
I/ActivityManager(  842): Killing 7269:com.test.thalitest/u0a200 (adj 0): stop com.test.thalitest
I/ActivityManager(  842):   Force finishing activity ActivityRecord{ca48bff u0 com.test.thalitest/.MainActivity t17}
D/FocusedStackFrame(  842): Set to : 0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SurfaceFlinger(  249): id=14 Removed com.test.thalitest/com.test.thalitest.MainActivity (6/8)
I/SurfaceFlinger(  249): id=14 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ConnectivityService(  842): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiService(  842): Client connection lost with reason: 4
I/ActivityManager(  842): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
I/art     ( 1547): Explicit concurrent mark sweep GC freed 12176(703KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 16MB/27MB, paused 385us total 27.730ms
I/art     ( 4549): Explicit concurrent mark sweep GC freed 5010(278KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 516us total 29.995ms
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  842): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1831): mOCRHelper is null
W/GeofencerStateMachine( 2197): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.4.503: ( 7484): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.503: ( 7484): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1454435172576
I/KLMS-2.4.503: ( 7484): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.503: ( 7484): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/SecContentProvider2(  842): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  842): mCursor = null
I/art     (  842): Explicit concurrent mark sweep GC freed 33234(3MB) AllocSpace objects, 60(960KB) LOS objects, 30% free, 36MB/52MB, paused 1.463ms total 151.397ms
D/ResourcesManager(  842): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  842): WaitForGcToComplete blocked for 79.030ms for cause Explicit
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/RegisteredServicesCache( 1454): empty dynamic service
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
E/Zygote  ( 8775): MountEmulatedStorage()
E/Zygote  ( 8775): v2
I/libpersona( 8775): KNOX_SDCARD checking this for 10104
I/libpersona( 8775): KNOX_SDCARD not a persona
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Books/Books.apk
I/ActivityManager(  842): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8775 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/SELinux ( 8775): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/SELinux ( 8775): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8775): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/TimaKeyStoreProvider( 8775): TimaSignature is unavailable
D/ActivityThread( 8775): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager( 8775): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/RCPManagerService(  842): PackageReceiver onReceive()
D/SurfaceWidgetView( 1471): destroyHardwareResources():364087497
I/HarmonyEASService(  842): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
V/WindowOrientationListener(  842): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  842): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  842): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  842): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  842): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/Launcher( 1471): onRestart, Launcher: 244897203
D/Launcher( 1471): onStart, Launcher: 244897203
D/Launcher.HomeView( 1471): onStart
D/KnoxMUMContainerPolicy(  842): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2058): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2058): [237392/6] SurfaceWidget drawing first frame
D/BackupManagerService(  842): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  842): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  842): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  842): uID is 10200
V/EnterpriseBillingPolicy(  842): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  842): getProfileForApplication - enter
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
V/EnterpriseBillingPolicyStorage(  842): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  842): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  842): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  842): getBillingProfileForVpnEngine - start - com.test.thalitest
I/SurfaceFlinger(  249): id=17 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
V/EnterpriseBillingPolicyStorage(  842): getBillingProfileForVpnEngine - end - null
D/StatusBarManagerService(  842): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/elm:14451( 8775): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8775): ELMEngine.ELMEngine( context ).
D/elm:14451( 8775): MDMBridge.setEnterpriseBridge()
D/StatusBarManagerService(  842): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/art     (  842): Explicit concurrent mark sweep GC freed 9054(422KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 36MB/52MB, paused 4.718ms total 188.628ms
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/TaskPersister(  842): removeObsoleteFile: deleting file=17_task.xml
D/elm:14451( 8775): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7938): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 7938): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7938): onReceive() : package name is not s health. Return !!!
D/elm:14451( 8775): ElmAgentService : onCreate()
D/elm:14451( 8775): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8775): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8775): MDMBridge.getInstance()
D/elm:14451( 8775): MDMBridge.getAllLicenseInfoFromSDK()
I/PCWCLIENTTRACE_PushUtil( 6699): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6699): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6699): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6699): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/elm:14451( 8775): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager( 7878): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourcesManager( 7878): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 7878): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
W/ResourcesManager( 7878): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/elm:14451( 8775): ElmAgentService : onDestroy().
D/ResourcesManager( 7878): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 7878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/InputMethodManagerService(  842): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/ResourcesManager( 7878): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/InputMethodManagerService(  842): Got RemoteException sending setActive(false) notification to pid 7269 uid 10200
E/Zygote  ( 8797): MountEmulatedStorage()
I/libpersona( 8797): KNOX_SDCARD checking this for 10038
E/Zygote  ( 8797): v2
I/libpersona( 8797): KNOX_SDCARD not a persona
I/ActivityManager(  842): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8797 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 8797): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  842): Killing 6145:com.google.android.gm/u0a114 (adj 15): bgCount ##41
I/SELinux ( 8797): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/ResourcesManager( 7878): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/ResourcesManager( 7878): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 7878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/SELinux ( 8797): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/PackageManager(  842): delete codoeFile: 
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/EnterpriseDeviceManagerService(  842): Package has changed for user 0
D/EnterpriseDeviceManagerService(  842): Admin package name: com.google.android.gms
D/ResourcesManager( 7878): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/ResourcesManager( 7878): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
D/PackageManager(  842): result of delete: 1{790987011}
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/TimaKeyStoreProvider( 8797): TimaSignature is unavailable
D/ActivityThread( 8797): Added TimaKeyStore provider
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager( 7878): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
I/Timeline(  842): Timeline: Activity_windows_visible id: ActivityRecord{3372cdfe u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t15} time:1296317
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Books/Books.apk
W/ResourcesManager( 7878): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager( 7878): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/AndroidRuntime( 8746): Shutting down VM
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Music2/Music2.apk
W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager( 7878): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ResourcesManager( 7878): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ResourcesManager( 8797): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager( 7878): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
W/ResourcesManager( 7878): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 7878): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 7878): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 7878): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/ResourcesManager( 7878): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 7878): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/ResourcesManager( 7878): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
W/ResourcesManager( 7878): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
E/SPPClientService( 8797): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 8797): [PushClientApplication] Push log off : This is Ship build version
D/ResourcesManager( 7878): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
W/libprocessgroup(  842): failed to open /acct/uid_10114/pid_6145/cgroup.procs: No such file or directory
W/ResourcesManager( 7878): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/SPPClientService( 8797): PushLog.txt file is not deleted.
D/SPPClientService( 8797): PushLog.txt file is not deleted.
D/SPPClientService( 8797): ============PushLog. stop!
W/ResourcesManager(  842): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  842): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  842): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
D/ResourcesManager(  842): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
D/ResourcesManager(  842): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  842): checkUser: useridlist=null, currentuser=0
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  842): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/Zygote  ( 8814): MountEmulatedStorage()
E/Zygote  ( 8814): v2
I/libpersona( 8814): KNOX_SDCARD checking this for 10042
I/libpersona( 8814): KNOX_SDCARD not a persona
D/ResourcesManager(  842): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/ActivityManager(  842): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8814 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/ActivityManager(  842): Killing 7111:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
W/Resources(  842): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager(  842): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  842): onPackageRemoved : com.test.thalitest
I/art     (  316): Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 270us total 15.632ms
I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 7.624ms
I/SELinux ( 8814): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 298us total 7.897ms
I/SELinux ( 8814): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8814): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL

```
